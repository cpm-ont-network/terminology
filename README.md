Markdown documentation created by [pyLODE](http://github.com/rdflib/pyLODE) 2.4

# The Construction Terminology (CTERM) Ontology

## Metadata
* **IRI**
  * `http://w3id.org/cterm`
* **Creators(s)**
  * [Cassandro, Jacopo](https://orcid.org/0000-0002-1487-8178)
    [[ORCID]](https://orcid.org/0000-0002-1487-8178)
    (<jacopo.cassandro@polimi.it></a>) of [Politecnico di Milano](https://www.dabc.polimi.it/persona/jacopo-cassandro/)
  * [Hagedorn, Philipp](https://orcid.org/0000-0002-6249-243X)
    [[ORCID]](https://orcid.org/0000-0002-6249-243X)
    (<philipp.hagedorn-n6v@rub.de></a>) of [Ruhr University Bochum, Computing in Engineering](https://www.inf.bi.ruhr-uni-bochum.de/iib/lehrstuhl/mitarbeiter/philipp_hagedorn.html.en)
* **Contributor(s)**
  * [Mirarchi, Claudio](https://orcid.org/0000-0002-9288-8662)
    [[ORCID]](https://orcid.org/0000-0002-9288-8662)
    (<claudio.mirarchi@polimi.it></a>) of [Politecnico di Milano, Dipartimento ABC](https://www.dabc.polimi.it/persona/claudio-mirarchi/)
  * [Sigalov, Katharina](https://orcid.org/0000-0002-3070-0759)
    [[ORCID]](https://orcid.org/0000-0002-3070-0759)
    (<katharina.sigalov@rub.de></a>) of [Ruhr University Bochum](https://www.inf.bi.ruhr-uni-bochum.de/iib/lehrstuhl/mitarbeiter/katharina_sigalov.html.en)
* **Created**
  * 2024-10-12
* **Modified**
  * 2025-04-07
* **Version Information**
  * 0.2
* **License &amp; Rights**
  * [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
  * &copy; 2025 by DABC, PoliMi
* **Ontology RDF**
  * RDF ([terminology.ttl](turtle))
* **Code Repository**
  * [https://github.com/cpm-ont-network/terminology](https://github.com/cpm-ont-network/terminology)
### Description
<p>The Construction Terminology (CTERM) Ontology is providing terminology to use with the Construction Resource (CR) and Cost Item (CI), as well as with the DTC ontology for the broader scope of construction project management.</p>

## Table of Contents
1. [Classes](#classes)
1. [Object Properties](#objectproperties)
1. [Datatype Properties](#datatypeproperties)
1. [Properties](#properties)
1. [Named Individuals](#namedindividuals)
1. [Namespaces](#namespaces)
1. [Legend](#legend)


## Overview

**Figure 1:** Ontology overview
## Classes
[Aspect](#Aspect),
[Aspect Of Equipment](#AspectOfEquipment),
[Aspect Of Material](#AspectOfMaterial),
[Aspect Of Work Of ConstructionWork](#AspectOfWorkOfConstructionWork),
[Aspect Of Work Of ProductWork](#AspectOfWorkOfProductWork),
[Aspect Of Work Of TemporaryWork](#AspectOfWorkOfTemporaryWork),
[Category](#Category),
[Category Of Activity](#CategoryOfActivity),
[Category Of CostComponent](#CategoryOfCostComponent),
[Category Of Work Of ConstructionWork](#CategoryOfWorkOfConstructionWork),
[Category Of Work Of ProductWork](#CategoryOfWorkOfProductWork),
[Category Of Work Of TemporaryWork](#CategoryOfWorkOfTemporaryWork),
[Category of equipment](#Categoryofequipment),
[Category of labour](#Categoryoflabour),
[Category of material](#Categoryofmaterial),
[Classification](#Classification),
[Classification system](#Classificationsystem),
[Dimension Parameter](#DimensionParameter),
[Dimension parameter type](#Dimensionparametertype),
[Family](#Family),
[Family of Activity](#FamilyofActivity),
[Family of CostComponent](#FamilyofCostComponent),
[Family of Work](#FamilyofWork),
[Family of equipment](#Familyofequipment),
[Family of labour](#Familyoflabour),
[Family of material](#Familyofmaterial),
[Finishing](#Finishing),
[Finishing Of Work Of ConstructionWork](#FinishingOfWorkOfConstructionWork),
[Finishing Of Work Of ProductWork](#FinishingOfWorkOfProductWork),
[Finishing Of Work Of TemporaryWork](#FinishingOfWorkOfTemporaryWork),
[Finishing of material](#Finishingofmaterial),
[Function](#Function),
[Function of equipment](#Functionofequipment),
[Function of material](#Functionofmaterial),
[FunctionOfActivity](#FunctionOfActivity),
[FunctionOfWorkOfConstructionWork](#FunctionOfWorkOfConstructionWork),
[FunctionOfWorkOfProductWork](#FunctionOfWorkOfProductWork),
[FunctionOfWorkOfTemporaryWork](#FunctionOfWorkOfTemporaryWork),
[Furnishing](#Furnishing),
[Material](#Material),
[Object](#Object),
[Object of equipment](#Objectofequipment),
[Object of labour](#Objectoflabour),
[Object of material](#Objectofmaterial),
[ObjectOfActivity](#ObjectOfActivity),
[ObjectOfCostComponent](#ObjectOfCostComponent),
[ObjectOfWorkOfConstructionWork](#ObjectOfWorkOfConstructionWork),
[ObjectOfWorkOfProductWork](#ObjectOfWorkOfProductWork),
[ObjectOfWorkOfTemporaryWork](#ObjectOfWorkOfTemporaryWork),
[Parameter](#Parameter),
[Parameter type](#Parametertype),
[Performance Parameter](#PerformanceParameter),
[Performance parameter type](#Performanceparametertype),
[Physical parameter type](#Physicalparametertype),
[PhysicalParameter](#PhysicalParameter),
[QualificationLevel](#QualificationLevel),
[Standard](#Standard),
[Terminology](#Terminology),
[Type](#Type),
[Type Of ProductWork](#TypeOfProductWork),
[Type Of TemporaryWork](#TypeOfTemporaryWork),
[Type Of Work Of ConstructionWork](#TypeOfWorkOfConstructionWork),
[Type Of Work Of ProductWork](#TypeOfWorkOfProductWork),
[Type Of Work Of TemporaryWork](#TypeOfWorkOfTemporaryWork),
[Type of construction work](#Typeofconstructionwork),
[Type of equipment](#Typeofequipment),
[Type of labour](#Typeoflabour),
[Type of material](#Typeofmaterial),
[TypeOfActivity](#TypeOfActivity),
[Use](#Use),
[Use Of Activity](#UseOfActivity),
[Use Of Work Of ConstructionWork](#UseOfWorkOfConstructionWork),
[Use Of Work Of ProductWork](#UseOfWorkOfProductWork),
[Use Of Work Of TemporaryWork](#UseOfWorkOfTemporaryWork),
[Use of equipment](#Useofequipment),
[Use of material](#Useofmaterial),
### Aspect
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Aspect`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:AspectOfWorkOfTemporaryWork](https://w3id.org/cterm#AspectOfWorkOfTemporaryWork) (c)<br />[cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork) (c)<br />[cterm:AspectOfEquipment](https://w3id.org/cterm#AspectOfEquipment) (c)<br />[cterm:AspectOfWorkOfProductWork](https://w3id.org/cterm#AspectOfWorkOfProductWork) (c)<br />[cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial) (c)<br />
In range of |[cterm:hasAspect](https://w3id.org/cterm#hasAspect) (op)<br />
### Aspect Of Equipment
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AspectOfEquipment`
Super-classes |[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />
### Aspect Of Material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AspectOfMaterial`
Super-classes |[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />
### Aspect Of Work Of ConstructionWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AspectOfWorkOfConstructionWork`
Super-classes |[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />
### Aspect Of Work Of ProductWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AspectOfWorkOfProductWork`
Super-classes |[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />
### Aspect Of Work Of TemporaryWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AspectOfWorkOfTemporaryWork`
Super-classes |[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />
### Category
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Category`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour) (c)<br />[cterm:CategoryOfWorkOfTemporaryWork](https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork) (c)<br />[cterm:CategoryOfEquipment](https://w3id.org/cterm#CategoryOfEquipment) (c)<br />[cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent) (c)<br />[cterm:CategoryOfActivity](https://w3id.org/cterm#CategoryOfActivity) (c)<br />[cterm:CategoryOfMaterial](https://w3id.org/cterm#CategoryOfMaterial) (c)<br />[cterm:CategoryOfWorkOfProductWork](https://w3id.org/cterm#CategoryOfWorkOfProductWork) (c)<br />[cterm:CategoryOfWorkOfConstructionWork](https://w3id.org/cterm#CategoryOfWorkOfConstructionWork) (c)<br />
In range of |[cterm:hasCategory](https://w3id.org/cterm#hasCategory) (op)<br />
### Category Of Activity
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CategoryOfActivity`
Super-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
### Category Of CostComponent
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CategoryOfCostComponent`
Super-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
### Category of equipment
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CategoryOfEquipment`
Super-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
### Category of labour
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CategoryOfLabour`
Super-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
### Category of material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CategoryOfMaterial`
Super-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
### Category Of Work Of ConstructionWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CategoryOfWorkOfConstructionWork`
Super-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
### Category Of Work Of ProductWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CategoryOfWorkOfProductWork`
Super-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
### Category Of Work Of TemporaryWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork`
Super-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
### Classification
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Classification`
Super-classes |[owl:Thing](http://www.w3.org/2002/07/owl#Thing) (c)<br />
Restrictions |[cterm:code](https://w3id.org/cterm#code) **exactly** 1 [xsd:string](http://www.w3.org/2001/XMLSchema#string) (c)<br />[cterm:hasClassificationSystem](https://w3id.org/cterm#hasClassificationSystem) (op) **exactly** 1 [cterm:ClassificationSystem](https://w3id.org/cterm#ClassificationSystem) (c)<br />
In domain of |[cterm:code](https://w3id.org/cterm#code)<br />[cterm:hasClassificationSystem](https://w3id.org/cterm#hasClassificationSystem) (op)<br />
In range of |[cterm:hasClassification](https://w3id.org/cterm#hasClassification) (op)<br />
### Classification system
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ClassificationSystem`
Super-classes |[owl:Thing](http://www.w3.org/2002/07/owl#Thing) (c)<br />
In range of |[cterm:hasClassificationSystem](https://w3id.org/cterm#hasClassificationSystem) (op)<br />
### Dimension Parameter
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DimensionParameter`
Super-classes |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Restrictions |[cterm:parameterType](https://w3id.org/cterm#parameterType) (op) **exactly** 1 [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType) (c)<br />
In range of |[cterm:hasDimensionParameter](https://w3id.org/cterm#hasDimensionParameter) (op)<br />
### Dimension parameter type
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DimensionParameterType`
Super-classes |[cterm:ParameterType](https://w3id.org/cterm#ParameterType) (c)<br />
### Family
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Family`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:FamilyOfActivity](https://w3id.org/cterm#FamilyOfActivity) (c)<br />[cterm:FamilyOfLabour](https://w3id.org/cterm#FamilyOfLabour) (c)<br />[cterm:FamilyOfEquipment](https://w3id.org/cterm#FamilyOfEquipment) (c)<br />[cterm:FamilyOfCostComponent](https://w3id.org/cterm#FamilyOfCostComponent) (c)<br />[cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial) (c)<br />[cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork) (c)<br />
In range of |[cterm:hasFamily](https://w3id.org/cterm#hasFamily) (op)<br />
### Family of Activity
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FamilyOfActivity`
Super-classes |[cterm:Family](https://w3id.org/cterm#Family) (c)<br />
### Family of CostComponent
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FamilyOfCostComponent`
Super-classes |[cterm:Family](https://w3id.org/cterm#Family) (c)<br />
### Family of equipment
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FamilyOfEquipment`
Super-classes |[cterm:Family](https://w3id.org/cterm#Family) (c)<br />
### Family of labour
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FamilyOfLabour`
Super-classes |[cterm:Family](https://w3id.org/cterm#Family) (c)<br />
### Family of material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FamilyOfMaterial`
Super-classes |[cterm:Family](https://w3id.org/cterm#Family) (c)<br />
### Family of Work
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FamilyOfWork`
Super-classes |[cterm:Family](https://w3id.org/cterm#Family) (c)<br />
### Finishing
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Finishing`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial) (c)<br />[cterm:FinishingOfWorkOfTemporaryWork](https://w3id.org/cterm#FinishingOfWorkOfTemporaryWork) (c)<br />[cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork) (c)<br />[cterm:FinishingOfWorkOfProductWork](https://w3id.org/cterm#FinishingOfWorkOfProductWork) (c)<br />
In range of |[cterm:hasFinishing](https://w3id.org/cterm#hasFinishing) (op)<br />
### Finishing of material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FinishingOfMaterial`
Super-classes |[cterm:Finishing](https://w3id.org/cterm#Finishing) (c)<br />
### Finishing Of Work Of ConstructionWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FinishingOfWorkOfConstructionWork`
Super-classes |[cterm:Finishing](https://w3id.org/cterm#Finishing) (c)<br />
### Finishing Of Work Of ProductWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FinishingOfWorkOfProductWork`
Super-classes |[cterm:Finishing](https://w3id.org/cterm#Finishing) (c)<br />
### Finishing Of Work Of TemporaryWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FinishingOfWorkOfTemporaryWork`
Super-classes |[cterm:Finishing](https://w3id.org/cterm#Finishing) (c)<br />
### Function
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Function`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:FunctionOfActivity](https://w3id.org/cterm#FunctionOfActivity) (c)<br />[cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork) (c)<br />[cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial) (c)<br />[cterm:FunctionOfEquipment](https://w3id.org/cterm#FunctionOfEquipment) (c)<br />[cterm:FunctionOfWorkOfProductWork](https://w3id.org/cterm#FunctionOfWorkOfProductWork) (c)<br />[cterm:FunctionOfWorkOfTemporaryWork](https://w3id.org/cterm#FunctionOfWorkOfTemporaryWork) (c)<br />
In range of |[cterm:hasFunction](https://w3id.org/cterm#hasFunction) (op)<br />
### FunctionOfActivity
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FunctionOfActivity`
Super-classes |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />
### Function of equipment
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FunctionOfEquipment`
Super-classes |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />
### Function of material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FunctionOfMaterial`
Super-classes |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />
### FunctionOfWorkOfConstructionWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FunctionOfWorkOfConstructionWork`
Super-classes |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />
### FunctionOfWorkOfProductWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FunctionOfWorkOfProductWork`
Super-classes |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />
### FunctionOfWorkOfTemporaryWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FunctionOfWorkOfTemporaryWork`
Super-classes |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />
### Furnishing
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Furnishing`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
In range of |[cterm:hasFurnishing](https://w3id.org/cterm#hasFurnishing) (op)<br />
### Material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Material`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
In range of |[cterm:hasMaterial](https://w3id.org/cterm#hasMaterial) (op)<br />
### Object
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Object`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment) (c)<br />[cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial) (c)<br />[cterm:ObjectOfWorkOfTemporaryWork](https://w3id.org/cterm#ObjectOfWorkOfTemporaryWork) (c)<br />[cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork) (c)<br />[cterm:ObjectOfWorkOfProductWork](https://w3id.org/cterm#ObjectOfWorkOfProductWork) (c)<br />[cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity) (c)<br />[cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent) (c)<br />[cterm:ObjectOfLabour](https://w3id.org/cterm#ObjectOfLabour) (c)<br />
In range of |[cterm:hasObject](https://w3id.org/cterm#hasObject) (op)<br />
### ObjectOfActivity
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ObjectOfActivity`
Super-classes |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
### ObjectOfCostComponent
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ObjectOfCostComponent`
Super-classes |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
### Object of equipment
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ObjectOfEquipment`
Super-classes |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
### Object of labour
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ObjectOfLabour`
Super-classes |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
### Object of material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ObjectOfMaterial`
Super-classes |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
### ObjectOfWorkOfConstructionWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ObjectOfWorkOfConstructionWork`
Super-classes |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
### ObjectOfWorkOfProductWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ObjectOfWorkOfProductWork`
Super-classes |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
### ObjectOfWorkOfTemporaryWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ObjectOfWorkOfTemporaryWork`
Super-classes |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
### Parameter
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Parameter`
Super-classes |[owl:Thing](http://www.w3.org/2002/07/owl#Thing) (c)<br />
Restrictions |[cterm:parameterValue2](https://w3id.org/cterm#parameterValue2) (dp) **max** 1<br />[cterm:hasUnit](https://w3id.org/cterm#hasUnit) (op) **max** 1 [qudt:Unit](http://qudt.org/schema/qudt/Unit) (c)<br />[cterm:parameterSymbol1](https://w3id.org/cterm#parameterSymbol1) (dp) **max** 1<br />[cterm:parameterSymbol2](https://w3id.org/cterm#parameterSymbol2) (dp) **max** 1<br />[cterm:hasParameterStandard](https://w3id.org/cterm#hasParameterStandard) (op) **max** 1 [cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />[cterm:parameterValue1](https://w3id.org/cterm#parameterValue1) (dp) **max** 1<br />
Sub-classes |[cterm:PerformanceParameter](https://w3id.org/cterm#PerformanceParameter) (c)<br />[cterm:DimensionParameter](https://w3id.org/cterm#DimensionParameter) (c)<br />[cterm:PhysicalParameter](https://w3id.org/cterm#PhysicalParameter) (c)<br />
In domain of |[cterm:hasParameterStandard](https://w3id.org/cterm#hasParameterStandard) (op)<br />[cterm:parameterSymbol2](https://w3id.org/cterm#parameterSymbol2) (dp)<br />[cterm:parameterValue1](https://w3id.org/cterm#parameterValue1) (dp)<br />[cterm:parameterSymbol1](https://w3id.org/cterm#parameterSymbol1) (dp)<br />[cterm:hasUnit](https://w3id.org/cterm#hasUnit) (op)<br />[cterm:parameterType](https://w3id.org/cterm#parameterType) (op)<br />[cterm:parameterValue2](https://w3id.org/cterm#parameterValue2) (dp)<br />
### Parameter type
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ParameterType`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType) (c)<br />[cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType) (c)<br />[cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType) (c)<br />
In range of |[cterm:parameterType](https://w3id.org/cterm#parameterType) (op)<br />
### Performance Parameter
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PerformanceParameter`
Super-classes |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Restrictions |[cterm:parameterType](https://w3id.org/cterm#parameterType) (op) **exactly** 1 [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType) (c)<br />
In range of |[cterm:hasPerformanceParameter](https://w3id.org/cterm#hasPerformanceParameter) (op)<br />
### Performance parameter type
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PerformanceParameterType`
Super-classes |[cterm:ParameterType](https://w3id.org/cterm#ParameterType) (c)<br />
### PhysicalParameter
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PhysicalParameter`
Super-classes |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Restrictions |[cterm:parameterType](https://w3id.org/cterm#parameterType) (op) **exactly** 1 [cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType) (c)<br />
In range of |[cterm:hasPhysicalParameter](https://w3id.org/cterm#hasPhysicalParameter) (op)<br />
### Physical parameter type
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PhysicalParameterType`
Super-classes |[cterm:ParameterType](https://w3id.org/cterm#ParameterType) (c)<br />
### QualificationLevel
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#QualificationLevel`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
In range of |[cterm:hasQualificationLevel](https://w3id.org/cterm#hasQualificationLevel) (op)<br />
### Standard
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Standard`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Restrictions |[cterm:standardNumber](https://w3id.org/cterm#standardNumber) (dp) **max** 1<br />[cterm:standardBody](https://w3id.org/cterm#standardBody) (dp) **max** 1<br />[cterm:standardPart](https://w3id.org/cterm#standardPart) (dp) **max** 1<br />[cterm:standardYear](https://w3id.org/cterm#standardYear) (dp) **max** 1<br />[cterm:standardPart](https://w3id.org/cterm#standardPart) (dp) **max** 1<br />[cterm:standardNumber](https://w3id.org/cterm#standardNumber) (dp) **max** 1<br />[cterm:standardYear](https://w3id.org/cterm#standardYear) (dp) **max** 1<br />[cterm:standardBody](https://w3id.org/cterm#standardBody) (dp) **max** 1<br />
In domain of |[cterm:standardNumber](https://w3id.org/cterm#standardNumber) (dp)<br />[cterm:standardBody](https://w3id.org/cterm#standardBody) (dp)<br />[cterm:standardPart](https://w3id.org/cterm#standardPart) (dp)<br />[cterm:standardYear](https://w3id.org/cterm#standardYear) (dp)<br />
In range of |[cterm:hasObjectStandard](https://w3id.org/cterm#hasObjectStandard) (op)<br />[cterm:hasParameterStandard](https://w3id.org/cterm#hasParameterStandard) (op)<br />[cterm:hasOtherStandard](https://w3id.org/cterm#hasOtherStandard) (op)<br />
### Terminology
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Terminology`
Super-classes |[owl:Thing](http://www.w3.org/2002/07/owl#Thing) (c)<br />
Sub-classes |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />[cterm:Type](https://w3id.org/cterm#Type) (c)<br />[cterm:Function](https://w3id.org/cterm#Function) (c)<br />[cterm:Furnishing](https://w3id.org/cterm#Furnishing) (c)<br />[cterm:Family](https://w3id.org/cterm#Family) (c)<br />[cterm:Use](https://w3id.org/cterm#Use) (c)<br />[cterm:Material](https://w3id.org/cterm#Material) (c)<br />[cterm:Object](https://w3id.org/cterm#Object) (c)<br />[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />[cterm:ParameterType](https://w3id.org/cterm#ParameterType) (c)<br />[cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel) (c)<br />[cterm:Finishing](https://w3id.org/cterm#Finishing) (c)<br />
### Type
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Type`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:TypeOfWorkOfProductWork](https://w3id.org/cterm#TypeOfWorkOfProductWork) (c)<br />[cterm:TypeOfWorkOfTemporaryWork](https://w3id.org/cterm#TypeOfWorkOfTemporaryWork) (c)<br />[cterm:TypeOfConstructionWork](https://w3id.org/cterm#TypeOfConstructionWork) (c)<br />[cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour) (c)<br />[cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment) (c)<br />[cterm:TypeOfTemporaryWork](https://w3id.org/cterm#TypeOfTemporaryWork) (c)<br />[cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork) (c)<br />[cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity) (c)<br />[cterm:TypeOfProductWork](https://w3id.org/cterm#TypeOfProductWork) (c)<br />[cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial) (c)<br />
In range of |[cterm:hasType](https://w3id.org/cterm#hasType) (op)<br />
### TypeOfActivity
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfActivity`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type of construction work
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfConstructionWork`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type of equipment
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfEquipment`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type of labour
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfLabour`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type of material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfMaterial`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type Of ProductWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfProductWork`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type Of TemporaryWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfTemporaryWork`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type Of Work Of ConstructionWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfWorkOfConstructionWork`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type Of Work Of ProductWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfWorkOfProductWork`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type Of Work Of TemporaryWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TypeOfWorkOfTemporaryWork`
Super-classes |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Use
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Use`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:UseOfActivity](https://w3id.org/cterm#UseOfActivity) (c)<br />[cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork) (c)<br />[cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment) (c)<br />[cterm:UseOfWorkOfProductWork](https://w3id.org/cterm#UseOfWorkOfProductWork) (c)<br />[cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork) (c)<br />[cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial) (c)<br />
In range of |[cterm:hasUse](https://w3id.org/cterm#hasUse) (op)<br />
### Use Of Activity
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UseOfActivity`
Super-classes |[cterm:Use](https://w3id.org/cterm#Use) (c)<br />
### Use of equipment
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UseOfEquipment`
Super-classes |[cterm:Use](https://w3id.org/cterm#Use) (c)<br />
### Use of material
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UseOfMaterial`
Super-classes |[cterm:Use](https://w3id.org/cterm#Use) (c)<br />
### Use Of Work Of ConstructionWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UseOfWorkOfConstructionWork`
Super-classes |[cterm:Use](https://w3id.org/cterm#Use) (c)<br />
### Use Of Work Of ProductWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UseOfWorkOfProductWork`
Super-classes |[cterm:Use](https://w3id.org/cterm#Use) (c)<br />
### Use Of Work Of TemporaryWork
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UseOfWorkOfTemporaryWork`
Super-classes |[cterm:Use](https://w3id.org/cterm#Use) (c)<br />

## Object Properties
[hasAspect](#hasAspect),
[hasCategory](#hasCategory),
[has classification](#hasclassification),
[has classification system](#hasclassificationsystem),
[hasDimensionParameter](#hasDimensionParameter),
[hasFamily](#hasFamily),
[hasFinishing](#hasFinishing),
[hasFunction](#hasFunction),
[hasFurnishing](#hasFurnishing),
[hasMaterial](#hasMaterial),
[hasObject](#hasObject),
[hasObjectStandard](#hasObjectStandard),
[hasOtherStandard](#hasOtherStandard),
[hasParameterStandard](#hasParameterStandard),
[hasPerformanceParameter](#hasPerformanceParameter),
[hasPhysicalParameter](#hasPhysicalParameter),
[hasQualificationLevel](#hasQualificationLevel),
[hasType](#hasType),
[hasUnit](#hasUnit),
[hasUse](#hasUse),
[parameter type](#parametertype),
[](hasAspect)
### hasAspect
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasAspect`
Domain(s) |([ci:Work](https://w3id.org/ci#Work) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />
[](hasCategory)
### hasCategory
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasCategory`
Domain(s) |([ci:CostComponent](https://w3id.org/ci#CostComponent) (c) or [ci:Work](https://w3id.org/ci#Work) (c) or [ci:Activity](https://w3id.org/ci#Activity) (c) or [cr:Resource](https://w3id.org/cr#Resource) (c))<br />
Range(s) |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
[](hasclassification)
### has classification
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasClassification`
Domain(s) |([ci:CostComponent](https://w3id.org/ci#CostComponent) (c) or [ci:CostItem](https://w3id.org/ci#CostItem) (c))<br />
Range(s) |[cterm:Classification](https://w3id.org/cterm#Classification) (c)<br />
[](hasclassificationsystem)
### has classification system
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasClassificationSystem`
Domain(s) |[cterm:Classification](https://w3id.org/cterm#Classification) (c)<br />
Range(s) |[cterm:ClassificationSystem](https://w3id.org/cterm#ClassificationSystem) (c)<br />
[](hasDimensionParameter)
### hasDimensionParameter
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasDimensionParameter`
Domain(s) |([ci:Work](https://w3id.org/ci#Work) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:DimensionParameter](https://w3id.org/cterm#DimensionParameter) (c)<br />
[](hasFamily)
### hasFamily
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasFamily`
Domain(s) |([ci:CostComponent](https://w3id.org/ci#CostComponent) (c) or [ci:Work](https://w3id.org/ci#Work) (c) or [ci:Activity](https://w3id.org/ci#Activity) (c) or [cr:Resource](https://w3id.org/cr#Resource) (c))<br />
Range(s) |[cterm:Family](https://w3id.org/cterm#Family) (c)<br />
[](hasFinishing)
### hasFinishing
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasFinishing`
Domain(s) |([ci:Work](https://w3id.org/ci#Work) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:Finishing](https://w3id.org/cterm#Finishing) (c)<br />
[](hasFunction)
### hasFunction
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasFunction`
Domain(s) |([ci:Work](https://w3id.org/ci#Work) (c) or [ci:Activity](https://w3id.org/ci#Activity) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />
[](hasFurnishing)
### hasFurnishing
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasFurnishing`
Domain(s) |[cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c)<br />
Range(s) |[cterm:Furnishing](https://w3id.org/cterm#Furnishing) (c)<br />
[](hasMaterial)
### hasMaterial
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasMaterial`
Domain(s) |([ci:CostComponent](https://w3id.org/ci#CostComponent) (c) or [ci:Work](https://w3id.org/ci#Work) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:Material](https://w3id.org/cterm#Material) (c)<br />
[](hasObject)
### hasObject
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasObject`
Domain(s) |([ci:CostComponent](https://w3id.org/ci#CostComponent) (c) or [ci:Work](https://w3id.org/ci#Work) (c) or [ci:Activity](https://w3id.org/ci#Activity) (c) or [cr:Resource](https://w3id.org/cr#Resource) (c))<br />
Range(s) |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
[](hasObjectStandard)
### hasObjectStandard
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasObjectStandard`
Domain(s) |([ci:CostComponent](https://w3id.org/ci#CostComponent) (c) or [ci:Work](https://w3id.org/ci#Work) (c) or [ci:Activity](https://w3id.org/ci#Activity) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />
[](hasOtherStandard)
### hasOtherStandard
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasOtherStandard`
Domain(s) |([ci:CostComponent](https://w3id.org/ci#CostComponent) (c) or [ci:Work](https://w3id.org/ci#Work) (c) or [ci:Activity](https://w3id.org/ci#Activity) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />
[](hasParameterStandard)
### hasParameterStandard
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasParameterStandard`
Domain(s) |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Range(s) |[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />
[](hasPerformanceParameter)
### hasPerformanceParameter
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasPerformanceParameter`
Domain(s) |([ci:Work](https://w3id.org/ci#Work) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:PerformanceParameter](https://w3id.org/cterm#PerformanceParameter) (c)<br />
[](hasPhysicalParameter)
### hasPhysicalParameter
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasPhysicalParameter`
Domain(s) |([ci:Work](https://w3id.org/ci#Work) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:PhysicalParameter](https://w3id.org/cterm#PhysicalParameter) (c)<br />
[](hasQualificationLevel)
### hasQualificationLevel
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasQualificationLevel`
Domain(s) |[cr:LabourResource](https://w3id.org/cr#LabourResource) (c)<br />
Range(s) |[cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel) (c)<br />
[](hasType)
### hasType
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasType`
Domain(s) |([ci:CostComponent](https://w3id.org/ci#CostComponent) (c) or [ci:Work](https://w3id.org/ci#Work) (c) or [ci:Activity](https://w3id.org/ci#Activity) (c) or [cr:Resource](https://w3id.org/cr#Resource) (c))<br />
Range(s) |[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
[](hasUnit)
### hasUnit
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasUnit`
Domain(s) |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Range(s) |[qudt:Unit](http://qudt.org/schema/qudt/Unit) (c)<br />
[](hasUse)
### hasUse
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasUse`
Domain(s) |([ci:Work](https://w3id.org/ci#Work) (c) or [ci:Activity](https://w3id.org/ci#Activity) (c) or [cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c) or [cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c))<br />
Range(s) |[cterm:Use](https://w3id.org/cterm#Use) (c)<br />
[](parametertype)
### parameter type
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#parameterType`
Domain(s) |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Range(s) |[cterm:ParameterType](https://w3id.org/cterm#ParameterType) (c)<br />

## Datatype Properties
[parameterSimbol1](#parameterSimbol1),
[parameterSimbol2](#parameterSimbol2),
[parameterValue1](#parameterValue1),
[parameterValue2](#parameterValue2),
[standardBody](#standardBody),
[standardNumber](#standardNumber),
[standardPart](#standardPart),
[standardYear](#standardYear),
[](parameterSimbol1)
### parameterSimbol1
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#parameterSymbol1`
Domain(s) |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Range(s) |[xsd:string](http://www.w3.org/2001/XMLSchema#string) (c)<br />
[](parameterSimbol2)
### parameterSimbol2
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#parameterSymbol2`
Domain(s) |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Range(s) |[xsd:string](http://www.w3.org/2001/XMLSchema#string) (c)<br />
[](parameterValue1)
### parameterValue1
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#parameterValue1`
Domain(s) |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Range(s) |[xsd:string](http://www.w3.org/2001/XMLSchema#string) (c)<br />
[](parameterValue2)
### parameterValue2
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#parameterValue2`
Domain(s) |[cterm:Parameter](https://w3id.org/cterm#Parameter) (c)<br />
Range(s) |[xsd:string](http://www.w3.org/2001/XMLSchema#string) (c)<br />
[](standardBody)
### standardBody
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#standardBody`
Domain(s) |[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />
Range(s) |[xsd:string](http://www.w3.org/2001/XMLSchema#string) (c)<br />
[](standardNumber)
### standardNumber
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#standardNumber`
Domain(s) |[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />
Range(s) |[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) (c)<br />
[](standardPart)
### standardPart
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#standardPart`
Domain(s) |[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />
Range(s) |[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) (c)<br />
[](standardYear)
### standardYear
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#standardYear`
Domain(s) |[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />
Range(s) |[xsd:integer](http://www.w3.org/2001/XMLSchema#integer) (c)<br />

## Properties
[code](#code),
[](code)
### code
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#code`
Domain(s) |[cterm:Classification](https://w3id.org/cterm#Classification) (c)<br />
Range(s) |[xsd:string](http://www.w3.org/2001/XMLSchema#string) (c)<br />

## Named Individuals
[5 Löcher](#5Lcher),
[6 Strands](#6Strands),
[A Mano](#AMano),
[Abdichtungen](#Abdichtungen),
[Abgehängte Decken](#AbgehngteDecken),
[Abriss](#Abriss),
[Accessori](#Accessori),
[Aggregate](#Aggregate),
[Agro Forestry](#AgroForestry),
[Akustik](#Akustik),
[Allgemeine Eisenlegierung](#AllgemeineEisenlegierung),
[Allgemeine Eisenlegierung](#GenericFerrousAlloySteel),
[Allgemeiner Gummi](#AllgemeinerGummi),
[Allgemeiner Naturstein](#AllgemeinerNaturstein),
[Allgemeines Bitumen](#AllgemeinesBitumen),
[Allgemeines Naturholz](#AllgemeinesNaturholz),
[Aluminum Foil](#AluminumFoil),
[Anti-Corrosive](#Anti-Corrosive),
[Application](#Application),
[Apprestamenti](#Apprestamenti),
[Architecture](#Architecture),
[Architravi](#Architravi),
[Arredo](#Arredo),
[Asphaltgemisch](#Asphaltgemisch),
[Auf Glas geglättet](#AufGlasgeglttet),
[Aus Halbvollen Blöcken](#AusHalbvollenBlcken),
[Aus Wabenblöcken](#AusWabenblcken),
[Ausbildung](#Ausbildung),
[Ausführung](#Ausfhrung),
[Aushub](#Aushub),
[Ausleger](#Ausleger),
[Autocarro con gru](#Autocarrocongru),
[Autoklavierter Porenbeton](#AutoklavierterPorenbeton),
[Badezimmer](#Badezimmer),
[Balken](#Balken),
[Bau](#Bau),
[Bauingenieurwesen](#Bauingenieurwesen),
[Baustellenzäune](#Baustellenzune),
[Bauwerk](#Bauwerk),
[Beam Edges and Curbs](#BeamEdgesandCurbs),
[Bedachungen](#Bedachungen),
[Betonstruktur](#Betonstruktur),
[Bewehrungen und Verstärkungen](#BewehrungenundVerstrkungen),
[Bianco](#Bianco),
[Bike Paths](#BikePaths),
[Binder](#Binder),
[Bird Repellent](#BirdRepellent),
[Bitume](#Bitume),
[Bodenbeläge](#Bodenbelge),
[Bodenhelfer für Hubschrauber](#BodenhelferfrHubschrauber),
[Bodenplatten](#Bodenplatten),
[Bordi Battentati/Incastro](#BordiBattentati/Incastro),
[Brandschutz](#Brandschutz),
[Brandschutztrennwand](#Brandschutztrennwand),
[Breite](#Breite),
[Brush](#Brush),
[Bulk](#Bulk),
[Buried Walls](#BuriedWalls),
[Bush-Hammered](#Bush-Hammered),
[Bäder-Küchen](#Bder-Kchen),
[Carta Kraft](#CartaKraft),
[Cartonfeltro Bitumato](#CartonfeltroBitumato),
[Casseri Per Strutture In Conglomerato Cementizio](#CasseriPerStruttureInConglomeratoCementizio),
[Cavities](#Cavities),
[Cellular Glass](#CellularGlass),
[Cementitious Compound](#CementitiousCompound),
[Cemetery](#Cemetery),
[Characteristic Strength](#CharacteristicStrength),
[Chemical Workers](#ChemicalWorkers),
[Chiusura](#Chiusura),
[Chiusura Frontale](#ChiusuraFrontale),
[Chiusura Laterale](#ChiusuraLaterale),
[Cleaning](#Cleaning),
[Coated with Fireproof Mortar](#CoatedwithFireproofMortar),
[Coated with Refractory Ceramic Layer](#CoatedwithRefractoryCeramicLayer),
[Coatings](#Coatings),
[Colore Giallo Dorata](#ColoreGialloDorata),
[Colore Grigio Oliva](#ColoreGrigioOliva),
[Colore Nero](#ColoreNero),
[Complementary](#Complementary),
[Complementary Systems](#ComplementarySystems),
[Compression Strength](#CompressionStrength),
[Con Mezzo Meccanico](#ConMezzoMeccanico),
[Concrete Mixer Truck](#ConcreteMixerTruck),
[Concrete Pours in Vertical Formwork](#ConcretePoursinVerticalFormwork),
[Concrete Structures](#ConcreteStructures),
[Conglomerate](#Conglomerate),
[Consistency](#Consistency),
[Continuous Foundations](#ContinuousFoundations),
[Controsoffitti](#Controsoffitti),
[Copertura Piana Carrabile](#CoperturaPianaCarrabile),
[Copertura Piana Con Pavimentazione Pedonabile](#CoperturaPianaConPavimentazionePedonabile),
[Copertura Ventilata A Falde](#CoperturaVentilataAFalde),
[Crack Repair](#CrackRepair),
[Curved-Oblique](#Curved-Oblique),
[Dachboden](#Dachboden),
[Dachschalung](#Dachschalung),
[Davanzali](#Davanzali),
[Deckschichten](#Deckschichten),
[Decontaminazione](#Decontaminazione),
[Densità](#Densit),
[Diaphragms](#Diaphragms),
[Differentiated Mesh](#DifferentiatedMesh),
[Dismantling](#Dismantling),
[Diwdag (Construction Technique)](#Diwdag(ConstructionTechnique)),
[Draining Synthetic Layer](#DrainingSyntheticLayer),
[Draining-Noise Absorbing Wearing Layer](#Draining-NoiseAbsorbingWearingLayer),
[Druck](#Druck),
[Drywall](#Drywall),
[Durchgangsbreite](#Durchgangsbreite),
[Durchmesser](#Durchmesser),
[Durchstoßfestigkeit](#Durchstofestigkeit),
[Dämmstoffe](#Dmmstoffe),
[Edifici](#Edifici),
[Ein Anstrich](#EinAnstrich),
[Einfache Betonstruktur](#EinfacheBetonstruktur),
[Einrichtung](#Einrichtung),
[Eisenlegierung Stahl B450A](#EisenlegierungStahlB450A),
[Eisenmetall](#Eisenmetall),
[Elastic Coating](#ElasticCoating),
[Elastic Modulus](#ElasticModulus),
[Electro-Welded Mesh](#Electro-WeldedMesh),
[Elektroingenieurwesen](#Elektroingenieurwesen),
[Elektroschmiedegitter](#Elektroschmiedegitter),
[Elettrosaldato](#Elettrosaldato),
[Ergotechnique](#Ergotechnique),
[Ersatz](#Ersatz),
[Excavation Systems](#ExcavationSystems),
[Expanded Clay](#ExpandedClay),
[Expanded Polyethylene Plastic](#ExpandedPolyethylenePlastic),
[Expanded Polystyrene Plastic (EPS)](#ExpandedPolystyrenePlastic(EPS)),
[Expandierter Korkpflanzenfaser](#ExpandierterKorkpflanzenfaser),
[Expositionsklasse](#Expositionsklasse),
[Exposure](#Exposure),
[External Surfaces](#ExternalSurfaces),
[Facciata Ventilata](#FacciataVentilata),
[Fahrmischer](#Fahrmischer),
[Fallhöhen](#Fallhhen),
[Fastenings](#Fastenings),
[Fenster und Türen](#FensterundTren),
[Ferrous Alloy Steel B450C](#FerrousAlloySteelB450C),
[Feuerwiderstand](#Feuerwiderstand),
[Fibra Minerale Lana Di Abete](#FibraMineraleLanaDiAbete),
[Fibra Minerale Lana Di Roccia Ad Alta Densità](#FibraMineraleLanaDiRocciaAdAltaDensit),
[Fibra Minerale Lana Di Vetro](#FibraMineraleLanaDiVetro),
[Fibra Vegetale Sughero](#FibraVegetaleSughero),
[Filo](#Filo),
[Filtering Geotextile](#FilteringGeotextile),
[Fire Protection Systems](#FireProtectionSystems),
[Fire Safety](#FireSafety),
[Fireproof Partition Wall](#FireproofPartitionWall),
[First Coat](#FirstCoat),
[Fixed Cranes](#FixedCranes),
[Fixed Cranes](#TowerCranes),
[Fixed Goal](#FixedGoal),
[Flat Roof](#FlatRoof),
[Flat Roofs](#FlatRoofs),
[Floor Slab](#FloorSlab),
[Floors](#Floors),
[Floors Over Unheated Areas](#FloorsOverUnheatedAreas),
[Flüsse](#Flsse),
[Fonoassorbente](#Fonoassorbente),
[Footings-Inverted Beams-Slabs](#Footings-InvertedBeams-Slabs),
[For Dam Construction](#ForDamConstruction),
[Formwork For Thermal Bridges](#FormworkForThermalBridges),
[Front mit Tür](#FrontmitTr),
[Fußboden](#Fuboden),
[Fußbodenunterlage](#Fubodenunterlage),
[Fußböden im Untergeschoss](#FubdenimUntergeschoss),
[Gas Impermeable Multilayer](#GasImpermeableMultilayer),
[Gebäudeausrüstung](#Gebudeausrstung),
[Gefärbt](#Gefrbt),
[Gelände](#Gelnde),
[Gelände/Hänge](#Gelnde/Hnge),
[Geländer für geradlinige Balkone aus Stahlbeton](#GelnderfrgeradlinigeBalkoneausStahlbeton),
[Generic](#Generic),
[Generic Cement](#GenericCement),
[Generic Engineered Wood](#GenericEngineeredWood),
[Generic Mineral Fiber](#GenericMineralFiber),
[Generic Structures](#GenericStructures),
[Gerade Treppenabsätze und Rampen](#GeradeTreppenabstzeundRampen),
[Gerade-Gebogene Achse](#Gerade-GebogeneAchse),
[Geschliffen](#Geschliffen),
[Gewindet](#Gewindet),
[Glass Fiber](#GlassFiber),
[Gomma Vulcanizzata](#GommaVulcanizzata),
[Graphite Expanded Polystyrene Plastic (EPS)](#GraphiteExpandedPolystyrenePlastic(EPS)),
[Graue Farbe](#GraueFarbe),
[Grünanlagen und Landschaftsbau](#GrnanlagenundLandschaftsbau),
[Guss](#Guss),
[Gün/Wald](#Gn/Wald),
[Heat Reflective](#HeatReflective),
[Hemp Vegetable Fiber](#HempVegetableFiber),
[Holzpflanzenfaser](#Holzpflanzenfaser),
[Hook Height](#HookHeight),
[HorizontalStructures](#HorizontalStructures),
[Horizontale Flächen](#HorizontaleFlchen),
[Housing Structural Elements](#HousingStructuralElements),
[Hubschrauberpilot](#Hubschrauberpilot),
[Höhe](#Hhe),
[ICT-Spezialist](#ICT-Spezialist),
[Idraulica](#Idraulica),
[Idrorepellente](#Idrorepellente),
[In Blocks](#InBlocks),
[In Hollow Blocks](#InHollowBlocks),
[In Perforated Bricks](#InPerforatedBricks),
[In Platten](#InPlatten),
[In Swiss-Type Blocks](#InSwiss-TypeBlocks),
[Incollaggio](#Incollaggio),
[Infrastrutture](#Infrastrutture),
[Ingegneria Idraulica](#IngegneriaIdraulica),
[Injection](#Injection),
[Innenbereich](#Innenbereich),
[Innenwände](#Innenwnde),
[Installazione](#Installazione),
[Instandhaltung](#Instandhaltung),
[Insulation Systems](#InsulationSystems),
[Intercapedini Perimetrali/Divisorie](#IntercapediniPerimetrali/Divisorie),
[Intermediate Floors](#IntermediateFloors),
[Internal Surfaces](#InternalSurfaces),
[Ironware](#Ironware),
[Kalk-Silikat-Mix](#Kalk-Silikat-Mix),
[Kalt](#Kalt),
[Kassettierungen](#Kassettierungen),
[Keramik, Terrakotta-Ziegel](#Keramik,Terrakotta-Ziegel),
[Konsolidierung](#Konsolidierung),
[Kontaminierte Standorte](#KontaminierteStandorte),
[Korngrößenverteilung](#Korngrenverteilung),
[Körnig](#Krnig),
[Küchen](#Kchen),
[Lack](#Lack),
[Lana Di Abete](#LanaDiAbete),
[Landschaftsbau](#Landschaftsbau),
[Laying](#Laying),
[Level B1](#LevelB1),
[Level C2](#LevelC2),
[Lightweight Concrete](#LightweightConcrete),
[Liscia Con Pelle](#LisciaConPelle),
[Load-Bearing](#Load-Bearing),
[Luftbewegung](#Luftbewegung),
[Lunghezza](#Lunghezza),
[Manuelle Steinentfernung](#ManuelleSteinentfernung),
[Marittime/Fluviali](#Marittime/Fluviali),
[Masonry](#Masonry),
[Masonry Layer](#MasonryLayer),
[Massetti](#Massetti),
[Mattbronze Farbe](#MattbronzeFarbe),
[Melange](#Melange),
[Membrana Armata Con Velo Vetro](#MembranaArmataConVeloVetro),
[Mesh](#Mesh),
[Metalworkers](#Metalworkers),
[Mineral Fiber Wood Wool](#MineralFiberWoodWool),
[Mineralfaser Steinwolle](#MineralfaserSteinwolle),
[Mineralized FirWool](#MineralizedFirWool),
[Mineralized Glass Fiber](#MineralizedGlassFiber),
[Mineralized Wood Vegetable Fiber](#MineralizedWoodVegetableFiber),
[Mineralized Wood Wool](#MineralizedWoodWool),
[Mischung](#Mischung),
[Mit Handgerät](#MitHandgert),
[Mit Mechanischen Und Manuellen Mitteln](#MitMechanischenUndManuellenMitteln),
[Mit verbesserter Haftung](#MitverbesserterHaftung),
[Mixed Slab with Deep Beams](#MixedSlabwithDeepBeams),
[Mobile Crane](#MobileCrane),
[Modifica](#Modifica),
[Montaggio](#Montaggio),
[Movimentazione](#Movimentazione),
[Mörtel](#Mrtel),
[Natural Blond Cork Vegetable Fiber](#NaturalBlondCorkVegetableFiber),
[Nennmaß-Durchmesser](#Nennma-Durchmesser),
[Netz](#Netz),
[Nicht brennbar](#Nichtbrennbar),
[Nicht strukturell](#Nichtstrukturell),
[Non-Relevant Generic Material](#Non-RelevantGenericMaterial),
[Normal Color](#NormalColor),
[Nutzpflanzen/Landwirtschaft](#Nutzpflanzen/Landwirtschaft),
[Oberfläche](#Oberflche),
[Oberqualifiziert](#Oberqualifiziert),
[Omniclass](#Omniclass),
[Ondulata](#Ondulata),
[Openings](#Openings),
[Operaio](#Operaio),
[Paneel](#Paneel),
[Paneele mit geraden Kanten](#PaneelemitgeradenKanten),
[Pannelli](#Pannelli),
[Pannello Rigido](#PannelloRigido),
[Parchi/Giardini/Aree Verdi](#Parchi/Giardini/AreeVerdi),
[Pareti](#Pareti),
[Pareti Con Sistema A Cappotto](#ParetiConSistemaACappotto),
[Pareti Dall Interno](#ParetiDallInterno),
[Pareti Esterne](#ParetiEsterne),
[Partition](#Partition),
[Partition Walls With Metal Structure](#PartitionWallsWithMetalStructure),
[Parzialmente Sublimante](#ParzialmenteSublimante),
[Pastellfarbe](#Pastellfarbe),
[Perimeter Cavities](#PerimeterCavities),
[Peso](#Peso),
[Piles](#Piles),
[Pillars](#Pillars),
[Pink Color](#PinkColor),
[Pitched Roof](#PitchedRoof),
[Pitched Roofs](#PitchedRoofs),
[Plasterboard](#Plasterboard),
[Plastered](#Plastered),
[Plastic Coating](#PlasticCoating),
[Plastic Film](#PlasticFilm),
[Plastic-Coated](#Plastic-Coated),
[Plastica Polistirene Estruso (XPS)](#PlasticaPolistireneEstruso(XPS)),
[Plastica Poliuretano Espanso (PIR)](#PlasticaPoliuretanoEspanso(PIR)),
[Point Foundations](#PointFoundations),
[Poliolefine](#Poliolefine),
[Polyethylen-Kunststoff (PE)](#Polyethylen-Kunststoff(PE)),
[Polyethylene Coated Kraft Paper](#PolyethyleneCoatedKraftPaper),
[Polymerbeschichtung](#Polymerbeschichtung),
[Polypropylene Film](#PolypropyleneFilm),
[Polypropylene Nonwoven Fabric Layer](#PolypropyleneNonwovenFabricLayer),
[Polyurethanlack](#Polyurethanlack),
[Pouring Walkway](#PouringWalkway),
[Power](#Power),
[Prefabricated](#Prefabricated),
[Production](#Production),
[Produkte](#Produkte),
[Prop](#Prop),
[Protection](#Protection),
[Pultdächer mit Dachziegeln](#PultdchermitDachziegeln),
[Pultdächer mit Ziegeln](#PultdchermitZiegeln),
[Pultruded](#Pultruded),
[Quilted Mat](#QuiltedMat),
[Randsteine](#Randsteine),
[Rau-Gesandstrahlt](#Rau-Gesandstrahlt),
[Rautenförmiges Netz](#RautenfrmigesNetz),
[Ready Mixture](#ReadyMixture),
[Realizzazione](#Realizzazione),
[Rebar](#Rebar),
[Rebated Edge Panels](#RebatedEdgePanels),
[Rechte Winkelkanten](#RechteWinkelkanten),
[Reconstruction](#Reconstruction),
[Rectangular Columns](#RectangularColumns),
[Refractory Ceramics](#RefractoryCeramics),
[Regulation Goal](#RegulationGoal),
[Reinforced Membrane With Polyester Nonwoven](#ReinforcedMembraneWithPolyesterNonwoven),
[Reinforced Slate Glass Fiber Membrane](#ReinforcedSlateGlassFiberMembrane),
[Reinforcing Bars](#ReinforcingBars),
[Reparatur](#Reparatur),
[Resistente All'Usura](#ResistenteAll'Usura),
[Resistenza A Compressione](#ResistenzaACompressione),
[Restoration](#Restoration),
[Retaining Walls](#RetainingWalls),
[Rigenerazione](#Rigenerazione),
[Rimozione](#Rimozione),
[Rivestito](#Rivestito),
[Rivestito Con Strato Ceramico Refrattario](#RivestitoConStratoCeramicoRefrattario),
[Rivestito Di Cartone Speciale](#RivestitoDiCartoneSpeciale),
[Road Works](#RoadWorks),
[Roadside Green](#RoadsideGreen),
[Roccia Naturale Perlite Espansa](#RocciaNaturalePerliteEspansa),
[Roccia Naturale Vermiculite Espansa](#RocciaNaturaleVermiculiteEspansa),
[Rollbar](#Rollbar),
[Roof garden](#Roofgarden),
[Roofing](#Roofing),
[Rough Floor Height](#RoughFloorHeight),
[Rough Without Skin](#RoughWithoutSkin),
[Rubber Compound](#RubberCompound),
[Ruvida](#Ruvida),
[Sandblasted](#Sandblasted),
[Scraping](#Scraping),
[Screed Formation](#ScreedFormation),
[Sechseckig](#Sechseckig),
[Seconda Mano](#SecondaMano),
[Self-Erecting Crane with Bottom Slewing](#Self-ErectingCranewithBottomSlewing),
[Self-Supporting Panels](#Self-SupportingPanels),
[Semi-Rigid Panel](#Semi-RigidPanel),
[Sewer/Water Pipes](#Sewer/WaterPipes),
[Sidewalks](#Sidewalks),
[Skin](#Skin),
[Sliding](#Sliding),
[Soil Consolidation](#SoilConsolidation),
[Soil Protection](#SoilProtection),
[Sottotetti Non Praticabili](#SottotettiNonPraticabili),
[Sottotetti Non Riscaldati](#SottotettiNonRiscaldati),
[Sottotetti Praticabili](#SottotettiPraticabili),
[Sound Absorption](#SoundAbsorption),
[Soundproof](#Soundproof),
[Specialized](#Specialized),
[Specialized Super](#SpecializedSuper),
[Specialized Super-Team Leader](#SpecializedSuper-TeamLeader),
[Spessore](#Spessore),
[Spezialmörtel (Gummigranulat, Polyurethanharze etc.)](#Spezialmrtel(Gummigranulat,Polyurethanharzeetc.)),
[Spielgeräte](#Spielgerte),
[Sportgeräte](#Sportgerte),
[Spray](#Spray),
[Square Mesh](#SquareMesh),
[StLB](#StLB),
[Stabilisierte Bodenbeläge](#StabilisierteBodenbelge),
[Stadtgrün](#Stadtgrn),
[Stainless](#Stainless),
[Stainless Steel Alloy](#StainlessSteelAlloy),
[Stainless Steel Alloy AISI 316L](#StainlessSteelAlloyAISI316L),
[Stampato](#Stampato),
[Starr](#Starr),
[Steinentfernung](#Steinentfernung),
[Stitching](#Stitching),
[Straight Stair Landings and Ramps in Reinforced Concrete](#StraightStairLandingsandRampsinReinforcedConcrete),
[Strands](#Strands),
[Strato Di Bitume](#StratoDiBitume),
[Strato Di Rivestimento](#StratoDiRivestimento),
[Straßen](#Straen),
[Straßensicherheit](#Straensicherheit),
[Structural Reinforcement](#StructuralReinforcement),
[Strukturell](#Strukturell),
[Struktursystem](#Struktursystem),
[Stufe 2](#Stufe2),
[Stufe 3](#Stufe3),
[Stufe C3](#StufeC3),
[Stufe D1](#StufeD1),
[Subfoundation](#Subfoundation),
[Suolo](#Suolo),
[Synthetic Compound](#SyntheticCompound),
[Synthetischer Gummi](#SynthetischerGummi),
[Systeme](#Systeme),
[Säcke](#Scke),
[T-Head](#T-Head),
[T1 Plaster](#T1Plaster),
[Teilweise](#Teilweise),
[Temporäre Zäune](#TemporreZune),
[Tensile Strength Perpendicular To Faces](#TensileStrengthPerpendicularToFaces),
[Termico](#Termico),
[Termoisolante](#Termoisolante),
[Thermal Bridges](#ThermalBridges),
[Thermal Conductivity](#ThermalConductivity),
[Thermal/Acoustic](#Thermal/Acoustic),
[Tischtennis](#Tischtennis),
[Tongue And Groove Panels](#TongueAndGroovePanels),
[Total Thickness](#TotalThickness),
[Tower crane rotating at the top](#Towercranerotatingatthetop),
[Traditionelle Holzschalung](#TraditionelleHolzschalung),
[Tragwerksplanung](#Tragwerksplanung),
[Transport](#Transport),
[Traspirante](#Traspirante),
[Trennwände](#Trennwnde),
[Two Layers](#TwoLayers),
[UNI8290](#UNI8290),
[Umgebung](#Umgebung),
[Underpinnings](#Underpinnings),
[Uniclass](#Uniclass),
[Uniformat](#Uniformat),
[Unterstützung](#Untersttzung),
[Velo Vetro Bitumato](#VeloVetroBitumato),
[Ventilazione](#Ventilazione),
[Verbindungen](#Verbindungen),
[Verkleidung](#Verkleidung),
[Verlegung von Hohlkörpern zur Belüftung](#VerlegungvonHohlkrpernzurBelftung),
[Verputzen](#Verputzen),
[Verschlüsse für Rohre](#VerschlssefrRohre),
[Verteilung](#Verteilung),
[Verteilungsklasse](#Verteilungsklasse),
[Vertikale Strukturen](#VertikaleStrukturen),
[Vogelabwehr-Dissuasor](#Vogelabwehr-Dissuasor),
[Vollbetonböden und -platten mit Balken in der Dicke](#Vollbetonbdenund-plattenmitBalkeninderDicke),
[Vollständig](#Vollstndig),
[Vor Ort](#VorOrt),
[Vorgeformte Paneele](#VorgeformtePaneele),
[Vorhandene Estriche](#VorhandeneEstriche),
[Vorsatzschale](#Vorsatzschale),
[Vulcanized Rock Wool](#VulcanizedRockWool),
[Wall-Ceiling](#Wall-Ceiling),
[Walls for Staircases and Elevators](#WallsforStaircasesandElevators),
[Wasserdampfdiffusionswiderstand](#Wasserdampfdiffusionswiderstand),
[Wasserdicht](#Wasserdicht),
[Wearing Layer](#WearingLayer),
[White Color](#WhiteColor),
[Widerstandsklasse](#Widerstandsklasse),
[With Crane](#WithCrane),
[With Pump](#WithPump),
[Wohngebiete](#Wohngebiete),
[Wood Wool](#WoodWool),
[Wooden Structures](#WoodenStructures),
[Wände in Höhe](#WndeinHhe),
[Wärmedämmend](#Wrmedmmend),
[Wärmewiderstand](#Wrmewiderstand),
[Zur Umgestaltung Und Wiederverwendung Zur Änderung Der Hydraulischen Anpassung](#ZurUmgestaltungUndWiederverwendungZurnderungDerHydraulischenAnpassung),
[Zwei Anstriche](#ZweiAnstriche),
[a cassa vuota](#acassavuota),
[a doppia torsione](#adoppiatorsione),
[a maglia sciolta](#amagliasciolta),
[antiriflesso](#antiriflesso),
[antisdrucciolo](#antisdrucciolo),
[antitrauma](#antitrauma),
[armato](#armato),
[armatura](#armatura),
[barre nervate](#barrenervate),
[barriere stradali](#barrierestradali),
[calce grassello](#calcegrassello),
[carico](#carico),
[cassaforma](#cassaforma),
[cassaforma componibile](#cassaformacomponibile),
[chimico](#chimico),
[classe di carico](#classedicarico),
[classe di consistenza](#classediconsistenza),
[classica-rustica](#classica-rustica),
[colore arancione](#colorearancione),
[colore rosso](#colorerosso),
[colore verde](#coloreverde),
[componenti](#componenti),
[componibile](#componibile),
[comune](#comune),
[conglomerato cementizio armato](#conglomeratocementizioarmato),
[controparete termoisolante-fonoassorbente](#controparetetermoisolante-fonoassorbente),
[corree](#corree),
[cuciture](#cuciture),
[da calcio](#dacalcio),
[delimitazioni-protezioni](#delimitazioni-protezioni),
[diametro testa](#diametrotesta),
[drenante](#drenante),
[edili](#edili),
[elementi provvisionali](#elementiprovvisionali),
[elettrificabile](#elettrificabile),
[elettrosaldata](#elettrosaldata),
[elevazione-fondazione](#elevazione-fondazione),
[entroterra](#entroterra),
[esterno](#esterno),
[fissa](#fissa),
[fissaggio](#fissaggio),
[fluido](#fluido),
[fondazione](#fondazione),
[forestale](#forestale),
[gesso generico](#gessogenerico),
[gioco piramide](#giocopiramide),
[gomma epdm](#gommaepdm),
[gru a torre a rotazione in alto](#gruatorrearotazioneinalto),
[impasti](#impasti),
[impianti idraulici terminali](#impiantiidrauliciterminali),
[in blocchi multiforo](#inblocchimultiforo),
[in blocchi pieni](#inblocchipieni),
[in pannelli](#inpannelli),
[in pannello modulare](#inpannellomodulare),
[in tavelle](#intavelle),
[isolante](#isolante),
[lega ferrosa acciaio inox AISI 304](#legaferrosaacciaioinoxAISI304),
[lega ferrosa acciaio inox AISI 304l](#legaferrosaacciaioinoxAISI304l),
[liscio](#liscio),
[livello 1°](#livello1),
[livello C1](#livelloC1),
[livello D2](#livelloD2),
[maglie esagonali](#maglieesagonali),
[massa volumica](#massavolumica),
[materiale generico](#materialegenerico),
[materiale poliammidico](#materialepoliammidico),
[metallo generico](#metallogenerico),
[movimentazione meccanizzata](#movimentazionemeccanizzata),
[muratura in mattoni pieni-pietrame-miste](#muraturainmattonipieni-pietrame-miste),
[murature vani scala-ascensori](#muraturevaniscala-ascensori),
[nervata](#nervata),
[paramassi](#paramassi),
[parapetti per balconi rettilinei](#parapettiperbalconirettilinei),
[pareti curvilinee in elevazione](#pareticurvilineeinelevazione),
[pavimentazione in gomma](#pavimentazioneingomma),
[pavimentazione sportiva](#pavimentazionesportiva),
[peso specifico](#pesospecifico),
[pilastri](#pilastri),
[pilastri a sezione rettangolare-quadrata](#pilastriasezionerettangolare-quadrata),
[pilastri circolari](#pilastricircolari),
[pompa autocarrata](#pompaautocarrata),
[pompe per cls](#pompepercls),
[portata](#portata),
[precompressione](#precompressione),
[prefabbricati per strutture in cls](#prefabbricatiperstruttureincls),
[puntello metallico](#puntellometallico),
[quadrata](#quadrata),
[qualificato](#qualificato),
[recinzioni](#recinzioni),
[resina sintetica acrilica](#resinasinteticaacrilica),
[resistenza a trazione](#resistenzaatrazione),
[resistenza al fuoco](#resistenzaalfuoco),
[rivestito in cartone speciale](#rivestitoincartonespeciale),
[sagomata](#sagomata),
[sbraccio](#sbraccio),
[semi-lavorati](#semi-lavorati),
[semiportante](#semiportante),
[sistemi di apprestamento di cantiere](#sistemidiapprestamentodicantiere),
[sistemi di fondazione](#sistemidifondazione),
[sistemi murari](#sistemimurari),
[solaio misto con travi in spessore per strutture piane](#solaiomistocontraviinspessoreperstrutturepiane),
[strato di base](#stratodibase),
[strato di binder](#stratodibinder),
[struttura](#struttura),
[struttura in pietra naturale dura](#strutturainpietranaturaledura),
[struttura in solaio misto](#strutturainsolaiomisto),
[strutture in conglomerato cementizio armato](#struttureinconglomeratocementizioarmato),
[strutture varie](#strutturevarie),
[superfici verticali](#superficiverticali),
[tamponamento](#tamponamento),
[terrazze](#terrazze),
[testa piatta](#testapiatta),
[tirantatura](#tirantatura),
[tradizionale](#tradizionale),
[traliccio](#traliccio),
[trefolo](#trefolo),
[tridimensionale a funi intrecciate](#tridimensionaleafuniintrecciate),
[vibratore per calcestruzzo](#vibratorepercalcestruzzo),
[zincata](#zincata),
[Überirdisch](#berirdisch),
### Überirdisch <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AboveGround`
* **Contributor(s)**
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### Accessori <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Accessories`
* **Contributor(s)**
  * [cterm:CategoryOfMaterial](https://w3id.org/cterm#CategoryOfMaterial)
### Akustik <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Acoustic`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Luftbewegung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AerialHandling`
* **Contributor(s)**
  * [cterm:CategoryOfEquipment](https://w3id.org/cterm#CategoryOfEquipment)
### Aggregate <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Aggregate`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### Nutzpflanzen/Landwirtschaft <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Agriculture`
* **Contributor(s)**
  * [cterm:FamilyOfLabour](https://w3id.org/cterm#FamilyOfLabour)
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Agro Forestry <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AgroForestry`
* **Contributor(s)**
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### Aluminum Foil <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AluminumFoil`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Anti-Corrosive <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Anti-Corrosive`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### antiriflesso <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Anti-Reflective`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### antisdrucciolo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Anti-Slip`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### antitrauma <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Anti-Trauma`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Application <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Application`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Architecture <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Architecture`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### sbraccio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Arm`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Montaggio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Assembly`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Unterstützung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Assistance`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Dachboden <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Attic`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Autoklavierter Porenbeton <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AutoclavedAeratedConcrete`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Säcke <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bags`
* **Contributor(s)**
  * [cterm:Furnishing](https://w3id.org/cterm#Furnishing)
### strato di base <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BaseLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Fußböden im Untergeschoss <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BasementFlooring`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Buried Walls <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BasementWalls`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Badezimmer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bathrooms`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Bäder-Küchen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bathrooms-Kitchens`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Beam Edges and Curbs <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BeamEdgesandCurbs`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Balken <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Beams`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Bike Paths <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BikePaths`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Binder <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Binder`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### strato di binder <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BinderLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Bird Repellent <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BirdRepellent`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Vogelabwehr-Dissuasor <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BirdRepellentDevice`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Bitume <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bitumen`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Strato Di Bitume <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BitumenLayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Cartonfeltro Bitumato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BituminizedFeltboard`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Velo Vetro Bitumato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BituminizedGlassFiber`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Asphaltgemisch <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BituminousMix`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Colore Nero <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BlackColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Melange <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Blend`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Ausleger <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Boom`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Traspirante <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Breathable`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Brush <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Brush`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Bau <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Building`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### Edifici <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Buildings`
* **Contributor(s)**
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### Bulk <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bulk`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Bush-Hammered <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bush-Hammered`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### portata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Capacity`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Kassettierungen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Casing`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Guss <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Casting`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Cavities <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Cavities`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Controsoffitti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Ceilings`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Cellular Glass <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CellularGlass`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Cementitious Compound <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CementitiousCompound`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:Material](https://w3id.org/cterm#Material)
### Cemetery <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Cemetery`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Keramik, Terrakotta-Ziegel <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CeramicTerracotta-Brick`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Characteristic Strength <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CharacteristicStrength`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### chimico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Chemical`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Chemical Workers <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ChemicalWorkers`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### pilastri circolari <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CircularColumns`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Bauingenieurwesen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CivilEngineering`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### classica-rustica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Classic-Rustic`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Cleaning <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Cleaning`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Chiusura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Closure`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Marittime/Fluviali <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Coastal_River`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Rivestito <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Coated`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Rivestito Con Strato Ceramico Refrattario <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatedWithRefractoryCeramicLayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Rivestito Di Cartone Speciale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatedWithSpecialCardboard`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Coated with Fireproof Mortar <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatedwithFireproofMortar`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Coated with Refractory Ceramic Layer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatedwithRefractoryCeramicLayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### rivestito in cartone speciale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatedwithSpecialCardboard`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Verkleidung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Coating`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Strato Di Rivestimento <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatingLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Coatings <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Coatings`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Kalt <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Cold`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Gefärbt <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Colored`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### pilastri <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Columns`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### comune <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Common`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Complementary <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Complementary`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Complementary Systems <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ComplementarySystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfConstructionWork](https://w3id.org/cterm#CategoryOfWorkOfConstructionWork)
### Vollständig <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Complete`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### componenti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Components`
* **Contributor(s)**
  * [cterm:CategoryOfMaterial](https://w3id.org/cterm#CategoryOfMaterial)
### Resistenza A Compressione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CompressionResistance`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Compression Strength <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CompressionStrength`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Concrete Mixer Truck <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConcreteMixerTruck`
* **Contributor(s)**
  * [cterm:Furnishing](https://w3id.org/cterm#Furnishing)
### Concrete Pours in Vertical Formwork <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConcretePoursinVerticalFormwork`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
### pompe per cls <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConcretePumps`
* **Contributor(s)**
  * [cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment)
### Betonstruktur <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConcreteStructure`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Concrete Structures <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConcreteStructures`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### vibratore per calcestruzzo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConcreteVibrator`
* **Contributor(s)**
  * [cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment)
### Conglomerate <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Conglomerate`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### corree <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConnectingBeams`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Verbindungen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Connections`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Consistency <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Consistency`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### classe di consistenza <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConsistencyClass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Konsolidierung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Consolidation`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Bauwerk <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Construction`
* **Contributor(s)**
  * [cterm:FamilyOfCostComponent](https://w3id.org/cterm#FamilyOfCostComponent)
  * [cterm:FamilyOfLabour](https://w3id.org/cterm#FamilyOfLabour)
### Baustellenzäune <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConstructionSiteFences`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### edili <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConstructionWorkers`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### Kontaminierte Standorte <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ContaminatedSites`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Continuous Foundations <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ContinuousFoundations`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Fibra Vegetale Sughero <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CorkVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Deckschichten <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoveringLayers`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Crack Repair <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CrackRepair`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Curved-Oblique <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Curved-Oblique`
* **Contributor(s)**
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### pareti curvilinee in elevazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CurvedWallsinElevation`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Decontaminazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Decontamination`
* **Contributor(s)**
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### delimitazioni-protezioni <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Delimitations-Protections`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Abriss <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Demolition`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
  * [cterm:CategoryOfActivity](https://w3id.org/cterm#CategoryOfActivity)
### Densità <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Density`
* **Contributor(s)**
  * [cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType)
### Durchmesser <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Diameter`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Diaphragms <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Diaphragms`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Differentiated Mesh <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DifferentiatedMesh`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Dismantling <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Dismantling`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Verteilung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Distribution`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Diwdag (Construction Technique) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Diwdag`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### a doppia torsione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DoubleTwist`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### drenante <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Draining`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Draining-Noise Absorbing Wearing Layer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Draining-NoiseAbsorbingWearingLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Draining Synthetic Layer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DrainingSyntheticLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Copertura Piana Carrabile <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DriveableFlatRoof`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Drywall <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Drywall`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### gomma epdm <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#EPDMRubber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Elastic Coating <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ElasticCoating`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Elastic Modulus <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ElasticModulus`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Elektroingenieurwesen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ElectricalEngineering`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### elettrificabile <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Electrifiable`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### elettrosaldata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Electro-Welded`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Electro-Welded Mesh <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Electro-WeldedMesh`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Elektroschmiedegitter <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Electroforged`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### elevazione-fondazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Elevation-Foundation`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Umgebung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Environment`
* **Contributor(s)**
  * [cterm:FamilyOfCostComponent](https://w3id.org/cterm#FamilyOfCostComponent)
### Ergotechnique <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Ergotechnique`
* **Contributor(s)**
  * [cterm:FamilyOfCostComponent](https://w3id.org/cterm#FamilyOfCostComponent)
### Aushub <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Excavation`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Excavation Systems <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExcavationSystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfTemporaryWork](https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork)
### Ausführung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Execution`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Vorhandene Estriche <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExistingScreeds`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Expanded Clay <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedClay`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Expandierter Korkpflanzenfaser <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedCorkVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Roccia Naturale Perlite Espansa <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedNaturalRockPerlite`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Roccia Naturale Vermiculite Espansa <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedNaturalRockVermiculite`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Expanded Polyethylene Plastic <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedPolyethylenePlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Expanded Polystyrene Plastic (EPS) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedPolystyrenePlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Exposure <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Exposure`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Expositionsklasse <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExposureClass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### esterno <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Exterior`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### External Surfaces <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExternalSurfaces`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Pareti Esterne <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExternalWalls`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Plastica Polistirene Estruso (XPS) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExtrudedPolystyrenePlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Fallhöhen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FallHeights`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### fissaggio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fastening`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Fastenings <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fastenings`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### recinzioni <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fences`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Eisenlegierung Stahl B450A <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FerrousAlloySteelB450A`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Ferrous Alloy Steel B450C <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FerrousAlloySteelB450C`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### tamponamento <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Filling`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Filtering Geotextile <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FilteringGeotextile`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Oberfläche <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Finish`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Lana Di Abete <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FirWool`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Fire Protection Systems <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireProtectionSystems`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Feuerwiderstand <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireReaction`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### resistenza al fuoco <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireResistance`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Fire Safety <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireSafety`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### Brandschutz <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fireproof`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Brandschutztrennwand <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireproofPartition`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Fireproof Partition Wall <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireproofPartitionWall`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### First Coat <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FirstCoat`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### 5 Löcher <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FiveHoles`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### fissa <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fixed`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Fixed Cranes <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FixedCranes`
* **Contributor(s)**
  * [cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment)
### Fixed Goal <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FixedGoal`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### testa piatta <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FlatHead`
* **Contributor(s)**
  * [cterm:AspectOfEquipment](https://w3id.org/cterm#AspectOfEquipment)
### Flat Roof <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FlatRoof`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Copertura Piana Con Pavimentazione Pedonabile <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FlatRoofWithWalkableSurface`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Flat Roofs <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FlatRoofs`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Fußboden <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Floor`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Floor Slab <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FloorSlab`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Bodenplatten <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FloorSlabs`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Fußbodenunterlage <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FloorUnderlay`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Bodenbeläge <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Flooring`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Floors <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Floors`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Floors Over Unheated Areas <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FloorsOverUnheatedAreas`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### fluido <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fluid`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Footings-Inverted Beams-Slabs <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Footings-InvertedBeams-Slabs`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### For Dam Construction <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ForDamConstruction`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### da calcio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ForFootball`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Zur Umgestaltung Und Wiederverwendung Zur Änderung Der Hydraulischen Anpassung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ForRemanipulationAndReuseForHydraulicAdjustment`
* **Contributor(s)**
  * [cterm:FunctionOfActivity](https://w3id.org/cterm#FunctionOfActivity)
### forestale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Forestry`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### Ausbildung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Forming`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### cassaforma <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Formwork`
* **Contributor(s)**
  * [cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment)
  * [cterm:ObjectOfWorkOfTemporaryWork](https://w3id.org/cterm#ObjectOfWorkOfTemporaryWork)
### Casseri Per Strutture In Conglomerato Cementizio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FormworkForReinforcedConcreteStructures`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Formwork For Thermal Bridges <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FormworkForThermalBridges`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### fondazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Foundation`
* **Contributor(s)**
  * [cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork)
### sistemi di fondazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FoundationSystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfConstructionWork](https://w3id.org/cterm#CategoryOfWorkOfConstructionWork)
### Chiusura Frontale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FrontClosure`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Front mit Tür <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FrontWithDoor`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Arredo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Furniture`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### zincata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Galvanized`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Gas Impermeable Multilayer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GasImpermeableMultilayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Generic <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Generic`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Allgemeines Bitumen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericBitumen`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:Material](https://w3id.org/cterm#Material)
### Generic Cement <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericCement`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Generic Engineered Wood <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericEngineeredWood`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Allgemeine Eisenlegierung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericFerrousAlloy`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Allgemeine Eisenlegierung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericFerrousAlloySteel`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### materiale generico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericMaterial`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### metallo generico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericMetal`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Generic Mineral Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericMineralFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Allgemeiner Naturstein <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericNaturalRock`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Allgemeines Naturholz <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericNaturalWood`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### gesso generico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericPlaster`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Allgemeiner Gummi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericRubber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Generic Structures <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericStructures`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Glass Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GlassFiber`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Incollaggio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Gluing`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Colore Giallo Dorata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GoldenYellowColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Körnig <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Granular`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Korngrößenverteilung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Granulometry`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Graphite Expanded Polystyrene Plastic (EPS) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GraphiteExpandedPolystyrenePlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Graue Farbe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GrayColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### colore verde <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Green`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Parchi/Giardini/Aree Verdi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GreenAreas`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Gün/Wald <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Green_Forest`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Grünanlagen und Landschaftsbau <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GreeneryandLandscaping`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Mörtel <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Grout`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Movimentazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Handling`
* **Contributor(s)**
  * [cterm:FamilyOfEquipment](https://w3id.org/cterm#FamilyOfEquipment)
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### struttura in pietra naturale dura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HardNaturalStoneStructure`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### diametro testa <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HeadDiameter`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Heat Reflective <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HeatReflective`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Höhe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Height`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Bodenhelfer für Hubschrauber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HelicopterGroundAssistant`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Hubschrauberpilot <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HelicopterPilot`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Hemp Vegetable Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HempVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Sechseckig <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Hexagonal`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### maglie esagonali <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HexagonalMesh`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Fibra Minerale Lana Di Roccia Ad Alta Densità <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HighDensityRockWool`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### a cassa vuota <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HollowBox`
* **Contributor(s)**
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### Hook Height <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HookHeight`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### HorizontalStructures <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HorizontalStructures`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Horizontale Flächen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HorizontalSurfaces`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Housing Structural Elements <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HousingStructuralElements`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Idraulica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Hydraulic`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### Ingegneria Idraulica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HydraulicEngineering`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### Mit verbesserter Haftung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ImprovedAdhesion`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### In Blocks <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### in tavelle <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InBricks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Hollow Blocks <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InHollowBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Aus Wabenblöcken <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InHoneycombBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### in pannello modulare <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InModularPanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### in blocchi multiforo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InMulti-HoleBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### in pannelli <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InPanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Perforated Bricks <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InPerforatedBricks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Aus Halbvollen Blöcken <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InSemi-SolidBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Platten <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InSlabs`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### in blocchi pieni <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InSolidBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Swiss-Type Blocks <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InSwiss-TypeBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Infrastrutture <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Infrastructure`
* **Contributor(s)**
  * [cterm:FamilyOfCostComponent](https://w3id.org/cterm#FamilyOfCostComponent)
### Injection <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Injection`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### entroterra <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Inland`
* **Contributor(s)**
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### Installazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Installation`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### isolante <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Insulation`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Insulation Systems <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InsulationSystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfConstructionWork](https://w3id.org/cterm#CategoryOfWorkOfConstructionWork)
### Dämmstoffe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Insulations`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Innenbereich <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Interior`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Intermediate Floors <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#IntermediateFloors`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Innenwände <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InternalPartitionWalls`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Internal Surfaces <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InternalSurfaces`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Pareti Dall Interno <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InternalWalls`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Eisenmetall <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#IronMetal`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Ironware <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Ironware`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### Küchen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Kitchens`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Carta Kraft <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#KraftPaper`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Gelände <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Land`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Gelände/Hänge <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LandSlopes`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Landschaftsbau <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Landscaping`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### Laying <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Laying`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Lunghezza <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Length`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### livello 1° <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Level1`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Stufe 2 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Level2`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Stufe 3 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Level3`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Level B1 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelB1`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### livello C1 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelC1`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Level C2 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelC2`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Stufe C3 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelC3`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Stufe D1 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelD1`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### livello D2 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelD2`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Lightweight Concrete <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LightweightConcrete`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Kalk-Silikat-Mix <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Lime-SilicaMixMaterial`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Architravi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Lintels`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### carico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Load`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Load-Bearing <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Load-Bearing`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### classe di carico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LoadClass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### a maglia sciolta <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LooseMesh`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Instandhaltung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Maintenance`
* **Contributor(s)**
  * [cterm:CategoryOfActivity](https://w3id.org/cterm#CategoryOfActivity)
### A Mano <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Manual`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Manuelle Steinentfernung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ManualStoneRemoval`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Masonry <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Masonry`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Masonry Layer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MasonryLayer`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork)
### Mattbronze Farbe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MatteBronzeColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Gebäudeausrüstung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MechanicalEngineering`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### movimentazione meccanizzata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MechanizedHandling`
* **Contributor(s)**
  * [cterm:CategoryOfEquipment](https://w3id.org/cterm#CategoryOfEquipment)
### Mesh <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Mesh`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### puntello metallico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MetalProp`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Metalworkers <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Metalworkers`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### Fibra Minerale Lana Di Abete <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralFiberFirWool`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Fibra Minerale Lana Di Vetro <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralFiberGlassWool`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Mineralfaser Steinwolle <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralFiberRockWool`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Mineral Fiber Wood Wool <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralFiberWoodWool`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Mineralized FirWool <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralizedFirWool`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Mineralized Glass Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralizedGlassFiber`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Mineralized Wood Vegetable Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralizedWoodVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Mineralized Wood Wool <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralizedWoodWool`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### struttura in solaio misto <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MixedSlabStructure`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Mixed Slab with Deep Beams <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MixedSlabwithDeepBeams`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### solaio misto con travi in spessore per strutture piane <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MixedSlabwithDeepBeamsforFlatStructures`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Mischung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Mixing`
* **Contributor(s)**
  * [cterm:CategoryOfEquipment](https://w3id.org/cterm#CategoryOfEquipment)
### impasti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Mixtures`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Mobile Crane <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MobileCrane`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Modifica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Modification`
* **Contributor(s)**
  * [cterm:FamilyOfActivity](https://w3id.org/cterm#FamilyOfActivity)
### componibile <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Modular`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfTemporaryWork](https://w3id.org/cterm#TypeOfWorkOfTemporaryWork)
### cassaforma componibile <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ModularFormwork`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Natural Blond Cork Vegetable Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#NaturalBlondCorkVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Netz <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Net`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### Nennmaß-Durchmesser <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#NominalDiameter`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Nicht brennbar <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Non-Combustible`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Non-Relevant Generic Material <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Non-RelevantGenericMaterial`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Nicht strukturell <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Non-Structural`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Sottotetti Non Riscaldati <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#NonHeatedAttics`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Sottotetti Non Praticabili <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#NonWalkableAttics`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Normal Color <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#NormalColor`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Colore Grigio Oliva <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#OliveGrayColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Omniclass <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Omniclass`
* **Contributor(s)**
  * [cterm:ClassificationSystem](https://w3id.org/cterm#ClassificationSystem)
### Vor Ort <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#OnSite`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Ein Anstrich <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#OneCoat`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Openings <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Openings`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### colore arancione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#OrangeColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Lack <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Paint`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Paneel <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Panel`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### Pannelli <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Panels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### Geländer für geradlinige Balkone aus Stahlbeton <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ParapetsforStraightBalconiesinReinforcedConcrete`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
### Teilweise <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Partial`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Parzialmente Sublimante <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PartiallySubliming`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Partition <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Partition`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Vorsatzschale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PartitionWall`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Trennwände <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PartitionWalls`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Partition Walls With Metal Structure <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PartitionWallsWithMetalStructure`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Durchgangsbreite <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PassageWidth`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Pastellfarbe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PastelColor`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Perimeter Cavities <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PerimeterCavities`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Intercapedini Perimetrali/Divisorie <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Perimeter_PartitionCavities`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Piles <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Piles`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Pillars <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Pillars`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Pink Color <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PinkColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Verschlüsse für Rohre <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PipeClosures`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Pitched Roof <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PitchedRoof`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Pitched Roofs <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PitchedRoofs`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Pultdächer mit Dachziegeln <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PitchedRoofsWithShingles`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Pultdächer mit Ziegeln <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PitchedRoofsWithTiles`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Plasterboard <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Plasterboard`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Plastered <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Plastered`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Verputzen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Plastering`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Plastic-Coated <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Plastic-Coated`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Plastic Coating <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PlasticCoating`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Plastic Film <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PlasticFilm`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Spielgeräte <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PlayEquipment`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Point Foundations <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PointFoundations`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Geschliffen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Polished`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### materiale poliammidico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyamideMaterial`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Polyethylene Coated Kraft Paper <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyethyleneCoatedKraftPaper`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Polyethylen-Kunststoff (PE) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyethylenePlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Polymerbeschichtung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolymericCoating`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Poliolefine <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Polyolefins`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Polypropylene Film <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolypropyleneFilm`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Polypropylene Nonwoven Fabric Layer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolypropyleneNonwovenFabricLayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Plastica Poliuretano Espanso (PIR) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyurethaneFoamPlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Polyurethanlack <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyurethanePaint`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Pouring Walkway <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PouringWalkway`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfTemporaryWork](https://w3id.org/cterm#TypeOfWorkOfTemporaryWork)
### Power <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Power`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### precompressione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Pre-Tensioning`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Prefabricated <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Prefabricated`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### prefabbricati per strutture in cls <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PrefabricatedStructuresInConcrete`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Vorgeformte Paneele <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PreformedPanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Apprestamenti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Preparations`
* **Contributor(s)**
  * [cterm:FamilyOfEquipment](https://w3id.org/cterm#FamilyOfEquipment)
### Druck <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Pressure`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Stampato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Printed`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Production <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Production`
* **Contributor(s)**
  * [cterm:FamilyOfActivity](https://w3id.org/cterm#FamilyOfActivity)
### Produkte <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Products`
* **Contributor(s)**
  * [cterm:CategoryOfMaterial](https://w3id.org/cterm#CategoryOfMaterial)
### Prop <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Prop`
* **Contributor(s)**
  * [cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment)
### Protection <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Protection`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### elementi provvisionali <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ProvisionalElements`
* **Contributor(s)**
  * [cterm:CategoryOfEquipment](https://w3id.org/cterm#CategoryOfEquipment)
### Pultruded <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Pultruded`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Durchstoßfestigkeit <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PunchingResistance`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### gioco piramide <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PyramidPlayStructure`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### qualificato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Qualified`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Oberqualifiziert <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#QualifiedSuper`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Quilted Mat <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#QuiltedMat`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Ready Mixture <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReadyMixture`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### Realizzazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Realization`
* **Contributor(s)**
  * [cterm:CategoryOfActivity](https://w3id.org/cterm#CategoryOfActivity)
### Rebar <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Rebar`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### Rebated Edge Panels <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RebatedEdgePanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Reconstruction <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Reconstruction`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### pilastri a sezione rettangolare-quadrata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Rectangular-SquareColumns`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
### Rectangular Columns <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RectangularColumns`
* **Contributor(s)**
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### colore rosso <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Red`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Refractory Ceramics <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RefractoryCeramics`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Rigenerazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Regeneration`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Regulation Goal <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RegulationGoal`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### armato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Reinforced`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### conglomerato cementizio armato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedConcrete`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### strutture in conglomerato cementizio armato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedConcreteStructures`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Membrana Armata Con Velo Vetro <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedMembraneWithGlassFiber`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Reinforced Membrane With Polyester Nonwoven <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedMembraneWithPolyesterNonwoven`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Reinforced Slate Glass Fiber Membrane <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedSlateGlassFiberMembrane`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### armatura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Reinforcement`
* **Contributor(s)**
  * [cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Bewehrungen und Verstärkungen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcementsandStrengthening`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Reinforcing Bars <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcingBars`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Rimozione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Removal`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Reparatur <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Repair`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Ersatz <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Replacement`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Wohngebiete <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Residences`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Widerstandsklasse <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ResistanceClass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Restoration <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Restoration`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Retaining Walls <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RetainingWalls`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Rautenförmiges Netz <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RhomboidMesh`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### nervata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Ribbed`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### barre nervate <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RibbedBars`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Rechte Winkelkanten <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RightAngleCorners`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Starr <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Rigid`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Pannello Rigido <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RigidPanel`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Flüsse <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Rivers`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### barriere stradali <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoadBarriers`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Straßensicherheit <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoadSafety`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Road Works <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoadWorks`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Straßen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Roads`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Roadside Green <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoadsideGreen`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### paramassi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RockfallBarriers`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Rollbar <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Rolling`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Roof garden <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoofGarden`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Dachschalung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoofPanelling`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Roofing <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Roofing`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Bedachungen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Roofs`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Ruvida <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Rough`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Rau-Gesandstrahlt <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Rough-Sandblasted`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Rough Floor Height <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoughFloorHeight`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Rough Without Skin <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoughWithoutSkin`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Rubber Compound <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RubberCompound`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### pavimentazione in gomma <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RubberFlooring`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Sandblasted <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Sandblasted`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Scraping <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Scraping`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Screed Formation <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ScreedFormation`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Massetti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Screeds`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### cuciture <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Seams`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Seconda Mano <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SecondCoat`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Self-Erecting Crane with Bottom Slewing <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Self-ErectingCranewithBottomSlewing`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Self-Supporting Panels <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Self-SupportingPanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### semi-lavorati <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Semi-FinishedProducts`
* **Contributor(s)**
  * [cterm:FamilyOfEquipment](https://w3id.org/cterm#FamilyOfEquipment)
### semiportante <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Semi-Load-Bearing`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Semi-Rigid Panel <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Semi-RigidPanel`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Einrichtung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Setups`
* **Contributor(s)**
  * [cterm:FamilyOfEquipment](https://w3id.org/cterm#FamilyOfEquipment)
### Sewer/Water Pipes <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SewerWaterPipes`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### sagomata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Shaped`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Chiusura Laterale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SideClosure`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Sidewalks <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Sidewalks`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Einfache Betonstruktur <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SimpleConcreteStructure`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### sistemi di apprestamento di cantiere <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SitePreparationSystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfTemporaryWork](https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork)
### 6 Strands <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SixStrands`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Skin <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Skin`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### calce grassello <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SlakedLime`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Sliding <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Sliding`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### liscio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Smooth`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Liscia Con Pelle <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SmoothWithSkin`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Auf Glas geglättet <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SmoothedonGlass`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Suolo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Soil`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Soil Consolidation <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SoilConsolidation`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Soil Protection <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SoilProtection`
* **Contributor(s)**
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### muratura in mattoni pieni-pietrame-miste <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SolidBrick-Stone-MixedMasonry`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Vollbetonböden und -platten mit Balken in der Dicke <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SolidSlabsandFloorsinReinforcedConcretewithDeepBeams`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Fonoassorbente <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SoundAbsorbing`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Sound Absorption <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SoundAbsorption`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Soundproof <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Soundproof`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Spezialmörtel (Gummigranulat, Polyurethanharze etc.) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpecialMortars`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
### Specialized <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Specialized`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Specialized Super <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpecializedSuper`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Specialized Super-Team Leader <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpecializedSuper-TeamLeader`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### ICT-Spezialist <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpecializedTechnicianforICTWork`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### peso specifico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpecificWeight`
* **Contributor(s)**
  * [cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType)
### Sportgeräte <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SportsEquipment`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### pavimentazione sportiva <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SportsFlooring`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Spray <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Spray`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Verteilungsklasse <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpreadClass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### quadrata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Square`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Square Mesh <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SquareMesh`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### StLB <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StLB`
* **Contributor(s)**
  * [cterm:ClassificationSystem](https://w3id.org/cterm#ClassificationSystem)
### Stabilisierte Bodenbeläge <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StabilizedEarthCarpets`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Stainless <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Stainless`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Stainless Steel Alloy <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StainlessSteelAlloy`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### lega ferrosa acciaio inox AISI 304 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StainlessSteelAlloyAISI304`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### lega ferrosa acciaio inox AISI 304l <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StainlessSteelAlloyAISI304l`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Stainless Steel Alloy AISI 316L <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StainlessSteelAlloyAISI316L`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### murature vani scala-ascensori <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Staircase-ElevatorShaftWalls`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Stitching <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Stitching`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Steinentfernung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StoneRemoval`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Gerade-Gebogene Achse <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Straight-CurvedAxis`
* **Contributor(s)**
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### parapetti per balconi rettilinei <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StraightBalconyParapets`
* **Contributor(s)**
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Paneele mit geraden Kanten <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StraightEdgePanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Gerade Treppenabsätze und Rampen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StraightStairLandingsandRamps`
* **Contributor(s)**
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Straight Stair Landings and Ramps in Reinforced Concrete <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StraightStairLandingsandRampsinReinforcedConcrete`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
### trefolo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Strand`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Strands <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Strands`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Randsteine <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Stringcourses`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Strukturell <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Structural`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Tragwerksplanung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StructuralEngineering`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### Structural Reinforcement <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StructuralReinforcement`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Struktursystem <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StructuralSystem`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfTemporaryWork](https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork)
### struttura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Structure`
* **Contributor(s)**
  * [cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork)
### Subfoundation <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Subfoundation`
* **Contributor(s)**
  * [cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork)
### Abgehängte Decken <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SuspendedCeilings`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### resina sintetica acrilica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SyntheticAcrylicResin`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Synthetic Compound <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SyntheticCompound`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Synthetischer Gummi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SyntheticRubber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Systeme <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Systems`
* **Contributor(s)**
  * [cterm:CategoryOfMaterial](https://w3id.org/cterm#CategoryOfMaterial)
### T-Head <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#T-Head`
* **Contributor(s)**
  * [cterm:AspectOfEquipment](https://w3id.org/cterm#AspectOfEquipment)
### T1 Plaster <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#T1Plaster`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Tischtennis <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TableTennis`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Temporäre Zäune <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TemporaryFences`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### resistenza a trazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TensileStrength`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Tensile Strength Perpendicular To Faces <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TensileStrengthPerpendicularToFaces`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### tirantatura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Tensioning`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### impianti idraulici terminali <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TerminalHydraulicSystems`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### terrazze <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Terraces`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Termico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Thermal`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Thermal Bridges <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalBridges`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Thermal Conductivity <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalConductivity`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Wärmedämmend <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalInsulating`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### controparete termoisolante-fonoassorbente <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalInsulatingandSoundAbsorbingPartitionWall`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Termoisolante <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalInsulation`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Wärmewiderstand <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalResistance`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Thermal/Acoustic <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Thermal_Acoustic`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Spessore <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Thickness`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Gewindet <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Threaded`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### tridimensionale a funi intrecciate <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThreeDimensionalBraidedRope`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Bordi Battentati/Incastro <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TongueAndGrooveEdges`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Tongue And Groove Panels <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TongueAndGroovePanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### gru a torre a rotazione in alto <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Top-SlewingTowerCrane`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Total Thickness <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TotalThickness`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Tower crane rotating at the top <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TowerCraneRotatingAtTheTop`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Fixed Cranes <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TowerCranes`
* **Contributor(s)**
  * [cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment)
### tradizionale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Traditional`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfTemporaryWork](https://w3id.org/cterm#TypeOfWorkOfTemporaryWork)
### Traditionelle Holzschalung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TraditionalWoodenFormwork`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Transport <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Transport`
* **Contributor(s)**
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### pompa autocarrata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Truck-MountedPump`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Fahrmischer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TruckMixer`
* **Contributor(s)**
  * [cterm:Furnishing](https://w3id.org/cterm#Furnishing)
### Autocarro con gru <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TruckwithCrane`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### traliccio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Truss`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Zwei Anstriche <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TwoCoats`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Two Layers <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TwoLayers`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### UNI8290 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UNI8290`
* **Contributor(s)**
  * [cterm:ClassificationSystem](https://w3id.org/cterm#ClassificationSystem)
### Underpinnings <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Underpinnings`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Uniclass <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Uniclass`
* **Contributor(s)**
  * [cterm:ClassificationSystem](https://w3id.org/cterm#ClassificationSystem)
### Uniformat <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Uniformat`
* **Contributor(s)**
  * [cterm:ClassificationSystem](https://w3id.org/cterm#ClassificationSystem)
### Stadtgrün <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UrbanGreen`
* **Contributor(s)**
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### strutture varie <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VariousStructures`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Verlegung von Hohlkörpern zur Belüftung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VentilatedCrawlSpaceFormation`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Facciata Ventilata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VentilatedFacade`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Copertura Ventilata A Falde <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VentilatedPitchedRoof`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Ventilazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Ventilation`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Vertikale Strukturen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VerticalStructures`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### superfici verticali <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VerticalSurfaces`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### massa volumica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VolumetricMass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Vulcanized Rock Wool <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VulcanizedRockWool`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Gomma Vulcanizzata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VulcanizedRubber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Sottotetti Praticabili <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WalkableAttics`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Wall-Ceiling <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Wall-Ceiling`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### sistemi murari <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WallSystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfTemporaryWork](https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork)
### Pareti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Walls`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Pareti Con Sistema A Cappotto <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WallsWithInsulatedPlasterSystem`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Walls for Staircases and Elevators <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WallsforStaircasesandElevators`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Wände in Höhe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WallsinElevation`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Idrorepellente <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WaterRepellent`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Wasserdampfdiffusionswiderstand <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WaterVaporDiffusionResistance`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Wasserdicht <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Waterproof`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Abdichtungen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Waterproofing`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Ondulata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Wavy`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Resistente All'Usura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Wear-Resistant`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Wearing Layer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WearingLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Peso <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Weight`
* **Contributor(s)**
  * [cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType)
### Elettrosaldato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Welded`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Bianco <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#White`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### White Color <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WhiteColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Breite <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Width`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Davanzali <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WindowSills`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Fenster und Türen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WindowsAndDoors`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Filo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Wire`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### With Crane <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WithCrane`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Mit Handgerät <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WithManualEquipment`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Mit Mechanischen Und Manuellen Mitteln <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WithMechanicalAndManualMeans`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Con Mezzo Meccanico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WithMechanicalMeans`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### With Pump <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WithPump`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Holzpflanzenfaser <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WoodVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Wood Wool <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WoodWool`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Wooden Structures <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WoodenStructures`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Operaio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Worker`
* **Contributor(s)**
  * [cterm:ObjectOfLabour](https://w3id.org/cterm#ObjectOfLabour)
## Namespaces
* **ci**
  * `https://w3id.org/ci#`
* **cr**
  * `https://w3id.org/cr#`
* **cterm**
  * `https://w3id.org/cterm#`
* **dc**
  * `http://purl.org/dc/terms/`
* **dtc**
  * `https://dtc-ontology.cms.ed.tum.de/ontology/`
* **owl**
  * `http://www.w3.org/2002/07/owl#`
* **prov**
  * `http://www.w3.org/ns/prov#`
* **qudt**
  * `http://qudt.org/schema/qudt/`
* **rdf**
  * `http://www.w3.org/1999/02/22-rdf-syntax-ns#`
* **rdfs**
  * `http://www.w3.org/2000/01/rdf-schema#`
* **sdo**
  * `https://schema.org/`
* **skos**
  * `http://www.w3.org/2004/02/skos/core#`
* **vann**
  * `http://purl.org/vocab/vann/`
* **vs**
  * `http://www.w3.org/2003/06/sw-vocab-status/ns#`
* **xml**
  * `http://www.w3.org/XML/1998/namespace`
* **xsd**
  * `http://www.w3.org/2001/XMLSchema#`

## Legend
* Classes: c
* Object Properties: op
* Functional Properties: fp
* Data Properties: dp
* Annotation Properties: dp
* Properties: p
* Named Individuals: ni