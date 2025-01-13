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
  * 2025-01-13
* **Version Information**
  * 0.1
* **Imports**
  * [http://w3id.org/ci](http://w3id.org/ci)
  * [http://w3id.org/cr](http://w3id.org/cr)
* **License &amp; Rights**
  * [https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
  * &copy; 2025 by DABC, PoliMi
* **Ontology RDF**
  * RDF ([terminology.ttl](turtle))
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
Sub-classes |[cterm:AspectOfWorkOfTemporaryWork](https://w3id.org/cterm#AspectOfWorkOfTemporaryWork) (c)<br />[cterm:AspectOfEquipment](https://w3id.org/cterm#AspectOfEquipment) (c)<br />[cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial) (c)<br />[cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork) (c)<br />[cterm:AspectOfWorkOfProductWork](https://w3id.org/cterm#AspectOfWorkOfProductWork) (c)<br />
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
Sub-classes |[cterm:CategoryOfWorkOfProductWork](https://w3id.org/cterm#CategoryOfWorkOfProductWork) (c)<br />[cterm:CategoryOfActivity](https://w3id.org/cterm#CategoryOfActivity) (c)<br />[cterm:CategoryOfMaterial](https://w3id.org/cterm#CategoryOfMaterial) (c)<br />[cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour) (c)<br />[cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent) (c)<br />[cterm:CategoryOfEquipment](https://w3id.org/cterm#CategoryOfEquipment) (c)<br />[cterm:CategoryOfWorkOfConstructionWork](https://w3id.org/cterm#CategoryOfWorkOfConstructionWork) (c)<br />[cterm:CategoryOfWorkOfTemporaryWork](https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork) (c)<br />
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
Restrictions |[cterm:hasClassificationSystem](https://w3id.org/cterm#hasClassificationSystem) (op) **exactly** 1 [cterm:ClassificationSystem](https://w3id.org/cterm#ClassificationSystem) (c)<br />[cterm:code](https://w3id.org/cterm#code) **exactly** 1<br />
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
Sub-classes |[cterm:FamilyOfLabour](https://w3id.org/cterm#FamilyOfLabour) (c)<br />[cterm:FamilyOfCostComponent](https://w3id.org/cterm#FamilyOfCostComponent) (c)<br />[cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial) (c)<br />[cterm:FamilyOfEquipment](https://w3id.org/cterm#FamilyOfEquipment) (c)<br />[cterm:FamilyOfActivity](https://w3id.org/cterm#FamilyOfActivity) (c)<br />[cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork) (c)<br />
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
Sub-classes |[cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork) (c)<br />[cterm:FinishingOfWorkOfTemporaryWork](https://w3id.org/cterm#FinishingOfWorkOfTemporaryWork) (c)<br />[cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial) (c)<br />[cterm:FinishingOfWorkOfProductWork](https://w3id.org/cterm#FinishingOfWorkOfProductWork) (c)<br />
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
Sub-classes |[cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial) (c)<br />[cterm:FunctionOfWorkOfTemporaryWork](https://w3id.org/cterm#FunctionOfWorkOfTemporaryWork) (c)<br />[cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork) (c)<br />[cterm:FunctionOfWorkOfProductWork](https://w3id.org/cterm#FunctionOfWorkOfProductWork) (c)<br />[cterm:FunctionOfEquipment](https://w3id.org/cterm#FunctionOfEquipment) (c)<br />[cterm:FunctionOfActivity](https://w3id.org/cterm#FunctionOfActivity) (c)<br />
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
Sub-classes |[cterm:ObjectOfLabour](https://w3id.org/cterm#ObjectOfLabour) (c)<br />[cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial) (c)<br />[cterm:ObjectOfWorkOfTemporaryWork](https://w3id.org/cterm#ObjectOfWorkOfTemporaryWork) (c)<br />[cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent) (c)<br />[cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment) (c)<br />[cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity) (c)<br />[cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork) (c)<br />[cterm:ObjectOfWorkOfProductWork](https://w3id.org/cterm#ObjectOfWorkOfProductWork) (c)<br />
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
Restrictions |[cterm:hasParameterStandard](https://w3id.org/cterm#hasParameterStandard) (op) **max** 1 [cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />[cterm:parameterSymbol1](https://w3id.org/cterm#parameterSymbol1) (dp) **max** 1<br />[cterm:parameterSymbol2](https://w3id.org/cterm#parameterSymbol2) (dp) **max** 1<br />[cterm:parameterValue2](https://w3id.org/cterm#parameterValue2) (dp) **max** 1<br />[cterm:hasUnit](https://w3id.org/cterm#hasUnit) (op) **max** 1 [qudt:Unit](http://qudt.org/schema/qudt/Unit) (c)<br />[cterm:parameterValue1](https://w3id.org/cterm#parameterValue1) (dp) **max** 1<br />
Sub-classes |[cterm:PerformanceParameter](https://w3id.org/cterm#PerformanceParameter) (c)<br />[cterm:PhysicalParameter](https://w3id.org/cterm#PhysicalParameter) (c)<br />[cterm:DimensionParameter](https://w3id.org/cterm#DimensionParameter) (c)<br />
In domain of |[cterm:parameterSymbol1](https://w3id.org/cterm#parameterSymbol1) (dp)<br />[cterm:hasUnit](https://w3id.org/cterm#hasUnit) (op)<br />[cterm:hasParameterStandard](https://w3id.org/cterm#hasParameterStandard) (op)<br />[cterm:parameterType](https://w3id.org/cterm#parameterType) (op)<br />[cterm:parameterSymbol2](https://w3id.org/cterm#parameterSymbol2) (dp)<br />[cterm:parameterValue1](https://w3id.org/cterm#parameterValue1) (dp)<br />[cterm:parameterValue2](https://w3id.org/cterm#parameterValue2) (dp)<br />
### Parameter type
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ParameterType`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType) (c)<br />[cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType) (c)<br />[cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType) (c)<br />
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
Restrictions |[cterm:standardBody](https://w3id.org/cterm#standardBody) (dp) **max** 1<br />[cterm:standardYear](https://w3id.org/cterm#standardYear) (dp) **max** 1<br />[cterm:standardPart](https://w3id.org/cterm#standardPart) (dp) **max** 1<br />[cterm:standardYear](https://w3id.org/cterm#standardYear) (dp) **max** 1<br />[cterm:standardNumber](https://w3id.org/cterm#standardNumber) (dp) **max** 1<br />[cterm:standardPart](https://w3id.org/cterm#standardPart) (dp) **max** 1<br />[cterm:standardBody](https://w3id.org/cterm#standardBody) (dp) **max** 1<br />[cterm:standardNumber](https://w3id.org/cterm#standardNumber) (dp) **max** 1<br />
In domain of |[cterm:standardPart](https://w3id.org/cterm#standardPart) (dp)<br />[cterm:standardYear](https://w3id.org/cterm#standardYear) (dp)<br />[cterm:standardNumber](https://w3id.org/cterm#standardNumber) (dp)<br />[cterm:standardBody](https://w3id.org/cterm#standardBody) (dp)<br />
In range of |[cterm:hasOtherStandard](https://w3id.org/cterm#hasOtherStandard) (op)<br />[cterm:hasObjectStandard](https://w3id.org/cterm#hasObjectStandard) (op)<br />[cterm:hasParameterStandard](https://w3id.org/cterm#hasParameterStandard) (op)<br />
### Terminology
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Terminology`
Super-classes |[owl:Thing](http://www.w3.org/2002/07/owl#Thing) (c)<br />
Sub-classes |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />[cterm:Use](https://w3id.org/cterm#Use) (c)<br />[cterm:Family](https://w3id.org/cterm#Family) (c)<br />[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />[cterm:Finishing](https://w3id.org/cterm#Finishing) (c)<br />[cterm:Furnishing](https://w3id.org/cterm#Furnishing) (c)<br />[cterm:Material](https://w3id.org/cterm#Material) (c)<br />[cterm:Category](https://w3id.org/cterm#Category) (c)<br />[cterm:Object](https://w3id.org/cterm#Object) (c)<br />[cterm:ParameterType](https://w3id.org/cterm#ParameterType) (c)<br />[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />[cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel) (c)<br />[cterm:Type](https://w3id.org/cterm#Type) (c)<br />
### Type
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Type`
Super-classes |[cterm:Terminology](https://w3id.org/cterm#Terminology) (c)<br />
Sub-classes |[cterm:TypeOfProductWork](https://w3id.org/cterm#TypeOfProductWork) (c)<br />[cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity) (c)<br />[cterm:TypeOfConstructionWork](https://w3id.org/cterm#TypeOfConstructionWork) (c)<br />[cterm:TypeOfWorkOfProductWork](https://w3id.org/cterm#TypeOfWorkOfProductWork) (c)<br />[cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment) (c)<br />[cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour) (c)<br />[cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork) (c)<br />[cterm:TypeOfWorkOfTemporaryWork](https://w3id.org/cterm#TypeOfWorkOfTemporaryWork) (c)<br />[cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial) (c)<br />[cterm:TypeOfTemporaryWork](https://w3id.org/cterm#TypeOfTemporaryWork) (c)<br />
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
Sub-classes |[cterm:UseOfWorkOfProductWork](https://w3id.org/cterm#UseOfWorkOfProductWork) (c)<br />[cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork) (c)<br />[cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork) (c)<br />[cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment) (c)<br />[cterm:UseOfActivity](https://w3id.org/cterm#UseOfActivity) (c)<br />[cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial) (c)<br />
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
[hasGender](#hasGender),
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
Domain(s) |[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />[cr:Material](https://w3id.org/cr#Material) (c)<br />
Range(s) |[cterm:Aspect](https://w3id.org/cterm#Aspect) (c)<br />
[](hasCategory)
### hasCategory
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasCategory`
Domain(s) |[ci:CostComponent](https://w3id.org/ci#CostComponent) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />[cr:Resource](https://w3id.org/cr#Resource) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />
Range(s) |[cterm:Category](https://w3id.org/cterm#Category) (c)<br />
[](hasclassification)
### has classification
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasClassification`
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
Domain(s) |[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />[cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c)<br />
Range(s) |[cterm:DimensionParameter](https://w3id.org/cterm#DimensionParameter) (c)<br />
[](hasFamily)
### hasFamily
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasFamily`
Domain(s) |[ci:Work](https://w3id.org/ci#Work) (c)<br />[cr:Resource](https://w3id.org/cr#Resource) (c)<br />[ci:CostComponent](https://w3id.org/ci#CostComponent) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />
Range(s) |[cterm:Family](https://w3id.org/cterm#Family) (c)<br />
[](hasFinishing)
### hasFinishing
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasFinishing`
Domain(s) |[ci:Work](https://w3id.org/ci#Work) (c)<br />[cr:Material](https://w3id.org/cr#Material) (c)<br />
Range(s) |[cterm:Finishing](https://w3id.org/cterm#Finishing) (c)<br />
[](hasFunction)
### hasFunction
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasFunction`
Domain(s) |[cr:Material](https://w3id.org/cr#Material) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />
Range(s) |[cterm:Function](https://w3id.org/cterm#Function) (c)<br />
[](hasFurnishing)
### hasFurnishing
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasFurnishing`
Domain(s) |[cr:Material](https://w3id.org/cr#Material) (c)<br />
Range(s) |[cterm:Furnishing](https://w3id.org/cterm#Furnishing) (c)<br />
[](hasGender)
### hasGender
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasGender`
Domain(s) |[cr:Resource](https://w3id.org/cr#Resource) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />[ci:CostComponent](https://w3id.org/ci#CostComponent) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />
[](hasMaterial)
### hasMaterial
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasMaterial`
Domain(s) |[ci:CostComponent](https://w3id.org/ci#CostComponent) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />[cr:Material](https://w3id.org/cr#Material) (c)<br />[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />
Range(s) |[cterm:Material](https://w3id.org/cterm#Material) (c)<br />
[](hasObject)
### hasObject
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasObject`
Domain(s) |[ci:Work](https://w3id.org/ci#Work) (c)<br />[ci:CostComponent](https://w3id.org/ci#CostComponent) (c)<br />[cr:Resource](https://w3id.org/cr#Resource) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />
Range(s) |[cterm:Object](https://w3id.org/cterm#Object) (c)<br />
[](hasObjectStandard)
### hasObjectStandard
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasObjectStandard`
Domain(s) |[ci:Work](https://w3id.org/ci#Work) (c)<br />[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />[cr:Material](https://w3id.org/cr#Material) (c)<br />[ci:CostComponent](https://w3id.org/ci#CostComponent) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />
Range(s) |[cterm:Standard](https://w3id.org/cterm#Standard) (c)<br />
[](hasOtherStandard)
### hasOtherStandard
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasOtherStandard`
Domain(s) |[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />[cr:Material](https://w3id.org/cr#Material) (c)<br />[ci:CostComponent](https://w3id.org/ci#CostComponent) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />
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
Domain(s) |[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />[cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c)<br />
Range(s) |[cterm:PerformanceParameter](https://w3id.org/cterm#PerformanceParameter) (c)<br />
[](hasPhysicalParameter)
### hasPhysicalParameter
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#hasPhysicalParameter`
Domain(s) |[cr:MaterialResource](https://w3id.org/cr#MaterialResource) (c)<br />[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />[ci:Work](https://w3id.org/ci#Work) (c)<br />
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
Domain(s) |[ci:Work](https://w3id.org/ci#Work) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />[ci:CostComponent](https://w3id.org/ci#CostComponent) (c)<br />[cr:Resource](https://w3id.org/cr#Resource) (c)<br />
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
Domain(s) |[ci:Work](https://w3id.org/ci#Work) (c)<br />[ci:Activity](https://w3id.org/ci#Activity) (c)<br />[cr:Material](https://w3id.org/cr#Material) (c)<br />[cr:EquipmentResource](https://w3id.org/cr#EquipmentResource) (c)<br />
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

## Named Individuals
[5 Holes](#5Holes),
[6 Strands](#6Strands),
[A Freddo](#AFreddo),
[A Mano](#AMano),
[A Pennello](#APennello),
[A Spruzzo](#ASpruzzo),
[Abdichtungen](#Abdichtungen),
[Abgehängte Decken](#AbgehngteDecken),
[Abspannung](#Abspannung),
[Accessories](#Accessories),
[Aggregate](#Aggregate),
[Agro Forestale](#AgroForestale),
[Akustik](#Akustik),
[Allgemein](#Allgemein),
[Allgemeines Material](#AllgemeinesMaterial),
[Allgemeines Metall](#AllgemeinesMetall),
[Allgemeines Naturholz](#AllgemeinesNaturholz),
[Allgemeines, nicht relevantes Material](#Allgemeines,nichtrelevantesMaterial),
[Aluminum Foil](#AluminumFoil),
[Antincendio](#Antincendio),
[Application](#Application),
[Apprestamenti](#Apprestamenti),
[Architettura](#Architettura),
[Argilla Espansa](#ArgillaEspansa),
[Arm](#Arm),
[Arredo](#Arredo),
[Attic](#Attic),
[Aushub](#Aushub),
[Ausleger](#Ausleger),
[Außenflächen](#Auenflchen),
[Bagni](#Bagni),
[Basement Flooring](#BasementFlooring),
[Bathrooms-Kitchens](#Bathrooms-Kitchens),
[Bauarbeiter](#Bauarbeiter),
[Bauingenieurwesen](#Bauingenieurwesen),
[Baustellenzäune](#Baustellenzune),
[Belüftetes Pultdach](#BelftetesPultdach),
[Belüftung](#Belftung),
[Betonstruktur](#Betonstruktur),
[Binder](#Binder),
[Bitume](#Bitume),
[Bitume Generico](#BitumeGenerico),
[Bitumen Layer](#BitumenLayer),
[Bituminized Feltboard](#BituminizedFeltboard),
[Bodenbelag](#Bodenbelag),
[Bodenplatten](#Bodenplatten),
[Bordi Battentati/Incastro](#BordiBattentati/Incastro),
[Brandschutz](#Brandschutz),
[Brandschutztrennwand](#Brandschutztrennwand),
[Breathable](#Breathable),
[Bush-Hammered](#Bush-Hammered),
[Böden über unbeheizten Bereichen](#BdenberunbeheiztenBereichen),
[Canali](#Canali),
[Carta Kraft Politenata](#CartaKraftPolitenata),
[Cavities](#Cavities),
[Ceilings](#Ceilings),
[Cementitious Compound](#CementitiousCompound),
[Cemetery](#Cemetery),
[Ceramic Terracotta-Brick](#CeramicTerracotta-Brick),
[Chemiearbeiter](#Chemiearbeiter),
[Chiusura](#Chiusura),
[Chiusura Frontale](#ChiusuraFrontale),
[Circular Columns](#CircularColumns),
[Classic-Rustic](#Classic-Rustic),
[Coastal/River](#Coastal/River),
[Coated With Special Cardboard](#CoatedWithSpecialCardboard),
[Coated with Special Cardboard](#CoatedwithSpecialCardboard),
[Coating Layer](#CoatingLayer),
[Colore Bianco](#ColoreBianco),
[Colore Nero](#ColoreNero),
[Colore Rosa](#ColoreRosa),
[Colture/Agricoltura](#Colture/Agricoltura),
[Columns](#Columns),
[Complete](#Complete),
[Con Mezzo Meccanico E Manuale](#ConMezzoMeccanicoEManuale),
[Concrete Mixer Truck](#ConcreteMixerTruck),
[Concrete Pours in Vertical Formwork](#ConcretePoursinVerticalFormwork),
[Condotte/Fogna/Acquedotto](#Condotte/Fogna/Acquedotto),
[Conducibilità Termica](#ConducibilitTermica),
[Connecting Beams](#ConnectingBeams),
[Connections](#Connections),
[Consolidamento](#Consolidamento),
[Contropareti Con Struttura Metallica](#ControparetiConStrutturaMetallica),
[Copertura A Falde](#CoperturaAFalde),
[Coperture](#Coperture),
[Coperture A Falde](#CopertureAFalde),
[Coperture A Falde Con Tegole](#CopertureAFaldeConTegole),
[Cork Vegetable Fiber](#CorkVegetableFiber),
[Costruzioni](#Costruzioni),
[Curved-Oblique](#Curved-Oblique),
[Davanzali](#Davanzali),
[Decontaminazione](#Decontaminazione),
[Demolition](#Demolition),
[Density](#Density),
[Diaphragmen](#Diaphragmen),
[Drainierende/Schallabsorbierende Deckschicht](#Drainierende/SchallabsorbierendeDeckschicht),
[Dreidimensionales Geflechtseil](#DreidimensionalesGeflechtseil),
[Driveable Flat Roof](#DriveableFlatRoof),
[Due Mani](#DueMani),
[Due Riprese](#DueRiprese),
[Dämmstoffe](#Dmmstoffe),
[Dämmsysteme](#Dmmsysteme),
[Edelstahllegierung](#Edelstahllegierung),
[Edelstahllegierung AISI 304](#EdelstahllegierungAISI304),
[Elastic Modulus](#ElasticModulus),
[Electro-Welded Mesh](#Electro-WeldedMesh),
[Elektroingenieurwesen](#Elektroingenieurwesen),
[Elektroschmiedegitter](#Elektroschmiedegitter),
[Elevation-Foundation](#Elevation-Foundation),
[Environment](#Environment),
[Ergänzend](#Ergnzend),
[Erster Anstrich](#ErsterAnstrich),
[Esecuzione](#Esecuzione),
[Estrich](#Estrich),
[Exposition](#Exposition),
[Exposure Class](#ExposureClass),
[Exterior](#Exterior),
[External Walls](#ExternalWalls),
[Facciata Ventilata](#FacciataVentilata),
[Facharbeiter](#Facharbeiter),
[Fachwerk](#Fachwerk),
[Fastenings](#Fastenings),
[Fences](#Fences),
[Fenster und Türen](#FensterundTren),
[Ferrous Alloy Steel B450A](#FerrousAlloySteelB450A),
[Ferrous Alloy Steel B450C](#FerrousAlloySteelB450C),
[Fertigteile für Betonstrukturen](#FertigteilefrBetonstrukturen),
[Feste Kräne](#FesteKrne),
[Fibra Minerale Lana Di Roccia Vulcanizzata](#FibraMineraleLanaDiRocciaVulcanizzata),
[Fibra Vegetale Canapa](#FibraVegetaleCanapa),
[Fibra Vegetale Sughero Biondo Naturale](#FibraVegetaleSugheroBiondoNaturale),
[Fibra Vegetale Sughero Espanso](#FibraVegetaleSugheroEspanso),
[Filling](#Filling),
[Finitura](#Finitura),
[Fire Reaction](#FireReaction),
[Fire Resistance](#FireResistance),
[Fixed Cranes](#FixedCranes),
[Flachdach](#Flachdach),
[Flachdach mit begehbarem Belag](#FlachdachmitbegehbaremBelag),
[Flat Head](#FlatHead),
[Flat Roofs](#FlatRoofs),
[Floor Slab](#FloorSlab),
[Floors](#Floors),
[Formazione Vespai Aerati](#FormazioneVespaiAerati),
[Forming](#Forming),
[Formwork For Reinforced Concrete Structures](#FormworkForReinforcedConcreteStructures),
[Forstwirtschaft](#Forstwirtschaft),
[Foundation Systems](#FoundationSystems),
[Frontale Con Porta](#FrontaleConPorta),
[Fundament](#Fundament),
[Fundamente-Umgekehrte Balken-Platten](#Fundamente-UmgekehrteBalken-Platten),
[Fußboden](#Fuboden),
[Für Fußball](#FrFuball),
[Galvanized](#Galvanized),
[Gebäude](#Gebude),
[Gebäudeausrüstung](#Gebudeausrstung),
[Gehwege](#Gehwege),
[Generic Ferrous Alloy Steel](#GenericFerrousAlloySteel),
[Generic Mineral Fiber](#GenericMineralFiber),
[Generic Natural Rock](#GenericNaturalRock),
[Generic Plaster](#GenericPlaster),
[Generic Rubber](#GenericRubber),
[Generic Structures](#GenericStructures),
[Generico](#Generico),
[Geotessile Filtrante](#GeotessileFiltrante),
[Geschliffen](#Geschliffen),
[Gewellt](#Gewellt),
[Gewicht](#Gewicht),
[Gewindet](#Gewindet),
[Glass Fiber](#GlassFiber),
[Glatt](#Glatt),
[Goldgelbe Farbe](#GoldgelbeFarbe),
[Gomma Vulcanizzata](#GommaVulcanizzata),
[Granular](#Granular),
[Graphite Expanded Polystyrene Plastic (EPS)](#GraphiteExpandedPolystyrenePlastic(EPS)),
[Gray Color](#GrayColor),
[Green](#Green),
[Green/Forest](#Green/Forest),
[Grout](#Grout),
[Grünanlagen und Landschaftsbau](#GrnanlagenundLandschaftsbau),
[Gummibodenbelag](#Gummibodenbelag),
[Guss](#Guss),
[Halbsteife Platte](#HalbsteifePlatte),
[Height](#Height),
[Helicopter Ground Assistant](#HelicopterGroundAssistant),
[Hexagonal](#Hexagonal),
[High Density Rock Wool](#HighDensityRockWool),
[Hinterland](#Hinterland),
[Holzstrukturen](#Holzstrukturen),
[Horizontal Surfaces](#HorizontalSurfaces),
[HorizontalStructures](#HorizontalStructures),
[Housing Structural Elements](#HousingStructuralElements),
[Hydraulic](#Hydraulic),
[Höhe unter Haken](#HheunterHaken),
[Impianti Antincendio](#ImpiantiAntincendio),
[In Bricks](#InBricks),
[In Honeycomb Blocks](#InHoneycombBlocks),
[In Modular Panels](#InModularPanels),
[In Multi-Hole Blocks](#InMulti-HoleBlocks),
[In Opera](#InOpera),
[In Slabs](#InSlabs),
[In Solid Blocks](#InSolidBlocks),
[Infrastrutture](#Infrastrutture),
[Injektion](#Injektion),
[Innenflächen](#Innenflchen),
[Installation](#Installation),
[Intercapedini Perimetrali](#IntercapediniPerimetrali),
[Intercapedini Perimetrali/Divisorie](#IntercapediniPerimetrali/Divisorie),
[Interior](#Interior),
[Intermediate Floors](#IntermediateFloors),
[Internal Partition Walls](#InternalPartitionWalls),
[Iron Metal](#IronMetal),
[Ironware](#Ironware),
[Isolamento Termico](#IsolamentoTermico),
[Isolierung](#Isolierung),
[Kalk-Silikat-Mix](#Kalk-Silikat-Mix),
[Kassettierungen](#Kassettierungen),
[Kitchens](#Kitchens),
[Komponenten](#Komponenten),
[Konsistenzklasse](#Konsistenzklasse),
[Kontaminierte Standorte](#KontaminierteStandorte),
[Korngrößenverteilung](#Korngrenverteilung),
[Korrosionsschutz](#Korrosionsschutz),
[Kraft Paper](#KraftPaper),
[Kunststoff Polyurethanschaum (PIR)](#KunststoffPolyurethanschaum(PIR)),
[Lack](#Lack),
[Lana Di Abete](#LanaDiAbete),
[Lana Di Legno](#LanaDiLegno),
[Land](#Land),
[Land/Slopes](#Land/Slopes),
[Level B1](#LevelB1),
[Level D2](#LevelD2),
[Lightweight Concrete](#LightweightConcrete),
[Lintels](#Lintels),
[Liscia Con Pelle](#LisciaConPelle),
[Litze](#Litze),
[Litzen](#Litzen),
[Load Class](#LoadClass),
[Loose Mesh](#LooseMesh),
[Lose](#Lose),
[Luftbewegung](#Luftbewegung),
[Lunghezza](#Lunghezza),
[Manutenzione](#Manutenzione),
[Masonry](#Masonry),
[Massetti Esistenti](#MassettiEsistenti),
[Materassino Trapuntato](#MaterassinoTrapuntato),
[Matte Bronze Color](#MatteBronzeColor),
[Melange](#Melange),
[Membrana Armata Con TNT Di Poliestere](#MembranaArmataConTNTDiPoliestere),
[Membrana Armata Con Velo Vetro Ardesiata](#MembranaArmataConVeloVetroArdesiata),
[Mesh](#Mesh),
[Metallstütze](#Metallsttze),
[Mineral Fiber Fir Wool](#MineralFiberFirWool),
[Mineral Fiber Glass Wool](#MineralFiberGlassWool),
[Mineral Fiber Wood Wool](#MineralFiberWoodWool),
[Mineralfaser Steinwolle](#MineralfaserSteinwolle),
[Mineralized FirWool](#MineralizedFirWool),
[Mineralized Glass Fiber](#MineralizedGlassFiber),
[Mineralized Wood Vegetable Fiber](#MineralizedWoodVegetableFiber),
[Mineralized Wood Wool](#MineralizedWoodWool),
[Mit Mechanischen Mitteln](#MitMechanischenMitteln),
[Mixed Slab with Deep Beams](#MixedSlabwithDeepBeams),
[Mixed Slab with Deep Beams for Flat Structures](#MixedSlabwithDeepBeamsforFlatStructures),
[Mixing](#Mixing),
[Mobile Crane](#MobileCrane),
[Modifica](#Modifica),
[Movimentazione](#Movimentazione),
[Multistrato Gas Impermeabile](#MultistratoGasImpermeabile),
[Net](#Net),
[Nominal Diameter](#NominalDiameter),
[Non Heated Attics](#NonHeatedAttics),
[Non-Combustible](#Non-Combustible),
[Non-Structural](#Non-Structural),
[Normale Farbe](#NormaleFarbe),
[Oben drehender Turmkran](#ObendrehenderTurmkran),
[Oberqualifiziert](#Oberqualifiziert),
[Olivgraue Farbe](#OlivgraueFarbe),
[One Coat](#OneCoat),
[Openings](#Openings),
[Orange Color](#OrangeColor),
[Paneele mit geraden Kanten](#PaneelemitgeradenKanten),
[Panels](#Panels),
[Pannelli A Bordi Risegati](#PannelliABordiRisegati),
[Pannelli Autoportanti](#PannelliAutoportanti),
[Pannelli Preformati](#PannelliPreformati),
[Pannello](#Pannello),
[Pannello Rigido](#PannelloRigido),
[Parapets for Straight Balconies in Reinforced Concrete](#ParapetsforStraightBalconiesinReinforcedConcrete),
[Pareti Dall Interno](#ParetiDallInterno),
[Parks/Gardens/Green Areas](#Parks/Gardens/GreenAreas),
[Passage Width](#PassageWidth),
[Pellicola Polipropilenica](#PellicolaPolipropilenica),
[Per Rimaneggiamento E Riutilizzo Per Variazione Della Conformazione Del Paraggio Idraulico](#PerRimaneggiamentoERiutilizzoPerVariazioneDellaConformazioneDelParaggioIdraulico),
[Pitched Roofs With Tiles](#PitchedRoofsWithTiles),
[Plasterboard](#Plasterboard),
[Plastic Coating](#PlasticCoating),
[Plastic Film](#PlasticFilm),
[Plastica Polietilene Espanso](#PlasticaPolietileneEspanso),
[Plastica Polistirene Espanso (EPS)](#PlasticaPolistireneEspanso(EPS)),
[Plastica Polistirene Estruso (XPS)](#PlasticaPolistireneEstruso(XPS)),
[Point Foundations](#PointFoundations),
[Polyamide Material](#PolyamideMaterial),
[Polyethylene Plastic (PE)](#PolyethylenePlastic(PE)),
[Polymeric Coating](#PolymericCoating),
[Polyolefins](#Polyolefins),
[Posa](#Posa),
[Power](#Power),
[Pre-Tensioning](#Pre-Tensioning),
[Pressure](#Pressure),
[Printed](#Printed),
[Produktion](#Produktion),
[Prop](#Prop),
[Protection](#Protection),
[Provisional Elements](#ProvisionalElements),
[Pulizia](#Pulizia),
[Pultruded](#Pultruded),
[Pyramid Play Structure](#PyramidPlayStructure),
[Quadratisches Netz](#QuadratischesNetz),
[Radwege](#Radwege),
[Rau ohne Beschichtung](#RauohneBeschichtung),
[Rau-Gesandstrahlt](#Rau-Gesandstrahlt),
[Ready Mixture](#ReadyMixture),
[Realizzazione](#Realizzazione),
[Rebar](#Rebar),
[Rechteckige Pfeiler](#RechteckigePfeiler),
[Refractory Ceramics](#RefractoryCeramics),
[Reinforced Concrete Structures](#ReinforcedConcreteStructures),
[Reinforced Membrane With Glass Fiber](#ReinforcedMembraneWithGlassFiber),
[Reinforcment](#Reinforcment),
[Removal](#Removal),
[Reparatur](#Reparatur),
[Residences](#Residences),
[Resistenza A Compressione](#ResistenzaACompressione),
[Resistenza A Compressione](#CompressionStrength),
[Resistenza A Trazione Perpendicolare Alle Facce](#ResistenzaATrazionePerpendicolareAlleFacce),
[Resistenza Alla Diffusione Del Vapore Acqueo](#ResistenzaAllaDiffusioneDelVaporeAcqueo),
[Restoration](#Restoration),
[Retaining Walls](#RetainingWalls),
[Rhomboid Mesh](#RhomboidMesh),
[Ribbed](#Ribbed),
[Ricostruzione](#Ricostruzione),
[Rigenerazione](#Rigenerazione),
[Rigid](#Rigid),
[Rigid Panels](#RigidPanels),
[Rivestimenti](#Rivestimenti),
[Rivestito Con Strato Ceramico Refrattario](#RivestitoConStratoCeramicoRefrattario),
[Road Safety](#RoadSafety),
[Roads](#Roads),
[Roccia Naturale Perlite Espansa](#RocciaNaturalePerliteEspansa),
[Roccia Naturale Vermiculite Espansa](#RocciaNaturaleVermiculiteEspansa),
[Roof garden](#Roofgarden),
[Roofs](#Roofs),
[Rough](#Rough),
[Rubber Compound](#RubberCompound),
[Rutschfest](#Rutschfest),
[Schallabsorption](#Schallabsorption),
[Schalldämpfend](#Schalldmpfend),
[Schalungen](#Schalungen),
[Schalungen für Wärmebrücken](#SchalungenfrWrmebrcken),
[Scraping](#Scraping),
[Screed Formation](#ScreedFormation),
[Seams](#Seams),
[Seconda Mano](#SecondaMano),
[Seitenverschluss](#Seitenverschluss),
[Self-Erecting Crane with Bottom Slewing](#Self-ErectingCranewithBottomSlewing),
[Site Setup Systems](#SiteSetupSystems),
[Skin](#Skin),
[Slaked Lime](#SlakedLime),
[Sliding](#Sliding),
[Smontaggio](#Smontaggio),
[Smoothed on Glass](#SmoothedonGlass),
[Soil Consolidation](#SoilConsolidation),
[Soil Protection](#SoilProtection),
[Solid Brick-Stone-Mixed Masonry](#SolidBrick-Stone-MixedMasonry),
[Sostituzione](#Sostituzione),
[Sotto Tavolati](#SottoTavolati),
[Sottopavimenti](#Sottopavimenti),
[Sottotetti Non Praticabili](#SottotettiNonPraticabili),
[Soundproof](#Soundproof),
[Special Mortars (Rubber Granules, Polyurethane Resins, etc.)](#SpecialMortars(RubberGranules,PolyurethaneResins,etc.)),
[Specialized Super-Team Leader](#SpecializedSuper-TeamLeader),
[Spezifisches Gewicht](#SpezifischesGewicht),
[Spielgeräte](#Spielgerte),
[Spietramento A Mano](#SpietramentoAMano),
[Spigoli Ad Angolo Retto](#SpigoliAdAngoloRetto),
[Stabilisierte Bodenbeläge](#StabilisierteBodenbelge),
[Stahlbeton](#Stahlbeton),
[Stainless Steel Alloy AISI 304l](#StainlessSteelAlloyAISI304l),
[Stainless Steel Alloy AISI 316L](#StainlessSteelAlloyAISI316L),
[Staircase-Elevator Shaft Walls](#Staircase-ElevatorShaftWalls),
[Standardtor](#Standardtor),
[Stone Removal](#StoneRemoval),
[Straight Stair Landings and Ramps in Reinforced Concrete](#StraightStairLandingsandRampsinReinforcedConcrete),
[Straight-Curved Axis](#Straight-CurvedAxis),
[Strato Di Muratura](#StratoDiMuratura),
[Strato Di Tessuto Non Tessuto Polipropilenico](#StratoDiTessutoNonTessutoPolipropilenico),
[Straßenbau](#Straenbau),
[Straßenbegleitgrün](#Straenbegleitgrn),
[Streifenfundamente](#Streifenfundamente),
[Stringcourses](#Stringcourses),
[Structural Engineering](#StructuralEngineering),
[Struktur aus Naturhartstein](#StrukturausNaturhartstein),
[Strukturell](#Strukturell),
[Strukturelle Verstärkung](#StrukturelleVerstrkung),
[Struktursystem](#Struktursystem),
[Stuccatura](#Stuccatura),
[Stufe 1](#Stufe1),
[Stufe C1](#StufeC1),
[Stufe C2](#StufeC2),
[Suolo](#Suolo),
[Synthetic Acrylic Resin](#SyntheticAcrylicResin),
[Säulen](#Sulen),
[T-Kopf](#T-Kopf),
[T1 Plaster](#T1Plaster),
[Teilweise](#Teilweise),
[Teilweise sublimierend](#Teilweisesublimierend),
[Terrassen](#Terrassen),
[Thermal](#Thermal),
[Thermal Insulating](#ThermalInsulating),
[Thermal Insulating and Sound Absorbing Partition Wall](#ThermalInsulatingandSoundAbsorbingPartitionWall),
[Thermal/Acoustic](#Thermal/Acoustic),
[Tischtennis](#Tischtennis),
[Tongue And Groove Panels](#TongueAndGroovePanels),
[Total Thickness](#TotalThickness),
[Traditional](#Traditional),
[Traditionelle Holzschalung](#TraditionelleHolzschalung),
[Tragend](#Tragend),
[Transport](#Transport),
[Trennwand](#Trennwand),
[Trennwände](#Trennwnde),
[Trockenbau](#Trockenbau),
[Truck with Crane](#TruckwithCrane),
[Turmdrehkran an der Oberseite](#TurmdrehkrananderOberseite),
[Unterfangungen](#Unterfangungen),
[Unterschiedliches Netz](#UnterschiedlichesNetz),
[Unterstützung](#Untersttzung),
[Urban Green](#UrbanGreen),
[Velo Vetro Bitumato](#VeloVetroBitumato),
[Verde E Paesaggio](#VerdeEPaesaggio),
[Verkleben](#Verkleben),
[Verkleidung](#Verkleidung),
[Verputzt](#Verputzt),
[Verschiedene Strukturen](#VerschiedeneStrukturen),
[Verschleißfest](#Verschleifest),
[Verschlüsse für Rohre](#VerschlssefrRohre),
[Verteilung](#Verteilung),
[Verteilungsklasse](#Verteilungsklasse),
[Vertical Structures](#VerticalStructures),
[Vetro Cellulare](#VetroCellulare),
[Vogelabwehr-Dissuasor](#Vogelabwehr-Dissuasor),
[Vorgefertigt](#Vorgefertigt),
[Walkable Attics](#WalkableAttics),
[Wall Systems](#WallSystems),
[Walls](#Walls),
[Walls With Insulated Plaster System](#WallsWithInsulatedPlasterSystem),
[Wasserabweisend](#Wasserabweisend),
[Wasserbauingenieurwesen](#Wasserbauingenieurwesen),
[Waterproof](#Waterproof),
[Welded](#Welded),
[White](#White),
[Width](#Width),
[Wire](#Wire),
[With Manual Equipment](#WithManualEquipment),
[With Pump](#WithPump),
[Wood Vegetable Fiber](#WoodVegetableFiber),
[Worker](#Worker),
[Wände für Treppen- und Aufzugsschächte](#WndefrTreppen-undAufzugsschchte),
[Wände im Untergeschoss](#WndeimUntergeschoss),
[Wärmebrücken](#Wrmebrcken),
[Wärmereflektierend](#Wrmereflektierend),
[Zugfestigkeit](#Zugfestigkeit),
[Zur Realisierung von Stauwerken](#ZurRealisierungvonStauwerken),
[Zusammenbau](#Zusammenbau),
[a cassa vuota](#acassavuota),
[a doppia torsione](#adoppiatorsione),
[ad aderenza migliorata](#adaderenzamigliorata),
[altezze di caduta](#altezzedicaduta),
[antipiccione](#antipiccione),
[antiriflesso](#antiriflesso),
[antitrauma](#antitrauma),
[apprestamenti](#apprestamenti),
[armato](#armato),
[armature e rinforzi](#armatureerinforzi),
[attrezzature sport](#attrezzaturesport),
[avvolgibile](#avvolgibile),
[barre nervate](#barrenervate),
[barriere stradali](#barrierestradali),
[capacità](#capacit),
[carico](#carico),
[cassaforma componibile](#cassaformacomponibile),
[cemento generico](#cementogenerico),
[chimico](#chimico),
[classe di resistenza](#classediresistenza),
[colorato](#colorato),
[colore pastello](#colorepastello),
[colore rosso](#colorerosso),
[componibile](#componibile),
[con gru](#congru),
[conglomerato](#conglomerato),
[conglomerato bituminoso](#conglomeratobituminoso),
[conglomerato cementizio aerato autoclavato](#conglomeratocementizioaeratoautoclavato),
[conglomerato sintetico](#conglomeratosintetico),
[consistenza](#consistenza),
[controparete](#controparete),
[controparete antincendio](#contropareteantincendio),
[cucitura](#cucitura),
[delimitazioni-protezioni](#delimitazioni-protezioni),
[diametro](#diametro),
[diametro testa](#diametrotesta),
[diwdag](#diwdag),
[drenante](#drenante),
[edile](#edile),
[elettrificabile](#elettrificabile),
[elettrosaldata](#elettrosaldata),
[elicotterista](#elicotterista),
[ergotecnica](#ergotecnica),
[ferri d'armatura](#ferrid'armatura),
[fissa](#fissa),
[fissaggio](#fissaggio),
[fluido](#fluido),
[gomma epdm](#gommaepdm),
[gomma sintetica](#gommasintetica),
[impasti](#impasti),
[impianti idraulici terminali](#impiantiidrauliciterminali),
[in blocchi](#inblocchi),
[in blocchi cavi](#inblocchicavi),
[in blocchi semipieni](#inblocchisemipieni),
[in blocchi tipo svizzero](#inblocchitiposvizzero),
[in pannelli](#inpannelli),
[in tavelle forate](#intavelleforate),
[inox](#inox),
[interpiano rustico](#interpianorustico),
[lega ferrosa generico](#legaferrosagenerico),
[legno artificiale generico](#legnoartificialegenerico),
[livello 2°](#livello2),
[livello 3°](#livello3),
[livello C3](#livelloC3),
[livello D1](#livelloD1),
[maglia esagonale](#magliaesagonale),
[manto sintetico drenante](#mantosinteticodrenante),
[massa volumica](#massavolumica),
[metalmeccanici](#metalmeccanici),
[movimentazione meccanizzata](#movimentazionemeccanizzata),
[pali](#pali),
[paramassi](#paramassi),
[parapetti per balconi rettilinei](#parapettiperbalconirettilinei),
[parete-soffitto](#parete-soffitto),
[pareti curvilinee in elevazione](#pareticurvilineeinelevazione),
[pareti in elevazione](#paretiinelevazione),
[passerella di getto](#passerelladigetto),
[pavimentazione sportiva](#pavimentazionesportiva),
[pianerottoli e rampe scale rettilinei](#pianerottolierampescalerettilinei),
[pilastri a sezione rettangolare-quadrata](#pilastriasezionerettangolare-quadrata),
[plastificata](#plastificata),
[pompa autocarrata](#pompaautocarrata),
[pompe per cls](#pompepercls),
[porta fissa](#portafissa),
[prodotti](#prodotti),
[quadrata](#quadrata),
[qualificato](#qualificato),
[recinzioni provvisorie](#recinzioniprovvisorie),
[resistenza a punzonamento](#resistenzaapunzonamento),
[resistenza caratteristica](#resistenzacaratteristica),
[resistenza termica](#resistenzatermica),
[rinforzo](#rinforzo),
[riparazione fessure](#riparazionefessure),
[rivestimento elastico](#rivestimentoelastico),
[rivestito](#rivestito),
[rivestito con malta antincendio](#rivestitoconmaltaantincendio),
[rivestito con strato di ceramica refrattaria](#rivestitoconstratodiceramicarefrattaria),
[sabbiato](#sabbiato),
[sacchi](#sacchi),
[sagomata](#sagomata),
[semi-lavorati](#semi-lavorati),
[semiportante](#semiportante),
[sistemi](#sistemi),
[sistemi complementari](#sistemicomplementari),
[sistemi di scavo](#sistemidiscavo),
[solai e solette piene in c.a. con travi a spessore](#solaiesolettepieneinc.a.contraviaspessore),
[sottofondazione](#sottofondazione),
[specializzato super](#specializzatosuper),
[spessore](#spessore),
[sponde di travi e cordoli](#spondeditraviecordoli),
[strati di copertura](#stratidicopertura),
[strato di base](#stratodibase),
[strato di binder](#stratodibinder),
[strato di usura](#stratodiusura),
[struttura](#struttura),
[struttura in conglomerato cementizio semplice](#strutturainconglomeratocementiziosemplice),
[struttura in solaio misto](#strutturainsolaiomisto),
[strutture in conglomerato cementizio](#struttureinconglomeratocementizio),
[superfici verticali](#superficiverticali),
[tecnico specialistico per lavorazioni ICT](#tecnicospecialisticoperlavorazioniICT),
[travi](#travi),
[vernice poliuretanica](#vernicepoliuretanica),
[vibratore per calcestruzzo](#vibratorepercalcestruzzo),
[Überirdisch](#berirdisch),
### Überirdisch <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AboveGround`
* **Contributor(s)**
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### Accessories <sup>c</sup>
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
### Colture/Agricoltura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Agriculture`
* **Contributor(s)**
  * [cterm:FamilyOfLabour](https://w3id.org/cterm#FamilyOfLabour)
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Agro Forestale <sup>c</sup>
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
### Korrosionsschutz <sup>c</sup>
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
### Rutschfest <sup>c</sup>
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
### Architettura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Architecture`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### Arm <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Arm`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Zusammenbau <sup>c</sup>
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
### Attic <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Attic`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### conglomerato cementizio aerato autoclavato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#AutoclavedAeratedConcrete`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### sacchi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bags`
* **Contributor(s)**
  * [cterm:FurnishingOfMaterial](https://w3id.org/cterm#FurnishingOfMaterial)
### strato di base <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BaseLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Basement Flooring <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BasementFlooring`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Wände im Untergeschoss <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BasementWalls`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Bagni <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bathrooms`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Bathrooms-Kitchens <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Bathrooms-Kitchens`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### sponde di travi e cordoli <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BeamEdgesandCurbs`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### travi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Beams`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Radwege <sup>c</sup>
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
### antipiccione <sup>c</sup>
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
### Bitumen Layer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#BitumenLayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Bituminized Feltboard <sup>c</sup>
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
### conglomerato bituminoso <sup>c</sup>
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
### Breathable <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Breathable`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### A Pennello <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Brush`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### edile <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Building`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### Gebäude <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Buildings`
* **Contributor(s)**
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### Lose <sup>c</sup>
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
### capacità <sup>c</sup>
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
### Ceilings <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Ceilings`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Vetro Cellulare <sup>c</sup>
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
  * [cterm:Material](https://w3id.org/cterm#Material)
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Cemetery <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Cemetery`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Ceramic Terracotta-Brick <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CeramicTerracotta-Brick`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### resistenza caratteristica <sup>c</sup>
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
### Chemiearbeiter <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ChemicalWorkers`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### Circular Columns <sup>c</sup>
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
### Classic-Rustic <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Classic-Rustic`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Pulizia <sup>c</sup>
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
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Coastal/River <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Coastal_River`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### rivestito <sup>c</sup>
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
### Coated With Special Cardboard <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatedWithSpecialCardboard`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### rivestito con malta antincendio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatedwithFireproofMortar`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### rivestito con strato di ceramica refrattaria <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatedwithRefractoryCeramicLayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Coated with Special Cardboard <sup>c</sup>
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
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Coating Layer <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoatingLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Rivestimenti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Coatings`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### A Freddo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Cold`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### colorato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Colored`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Columns <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Columns`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Allgemein <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Common`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Ergänzend <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Complementary`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### sistemi complementari <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ComplementarySystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfConstructionWork](https://w3id.org/cterm#CategoryOfWorkOfConstructionWork)
### Complete <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Complete`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Komponenten <sup>c</sup>
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
### Resistenza A Compressione <sup>c</sup>
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
  * [cterm:FurnishingOfMaterial](https://w3id.org/cterm#FurnishingOfMaterial)
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
### strutture in conglomerato cementizio <sup>c</sup>
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
### conglomerato <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Conglomerate`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Connecting Beams <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConnectingBeams`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Connections <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Connections`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### consistenza <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Consistency`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Konsistenzklasse <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConsistencyClass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Consolidamento <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Consolidation`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Costruzioni <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Construction`
* **Contributor(s)**
  * [cterm:FamilyOfLabour](https://w3id.org/cterm#FamilyOfLabour)
  * [cterm:FamilyOfCostComponent](https://w3id.org/cterm#FamilyOfCostComponent)
### Baustellenzäune <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ConstructionSiteFences`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Bauarbeiter <sup>c</sup>
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
### Streifenfundamente <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ContinuousFoundations`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Cork Vegetable Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CorkVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### strati di copertura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#CoveringLayers`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### riparazione fessure <sup>c</sup>
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
### Demolition <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Demolition`
* **Contributor(s)**
  * [cterm:CategoryOfActivity](https://w3id.org/cterm#CategoryOfActivity)
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Density <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Density`
* **Contributor(s)**
  * [cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType)
### diametro <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Diameter`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Diaphragmen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Diaphragms`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Unterschiedliches Netz <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DifferentiatedMesh`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Smontaggio <sup>c</sup>
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
### diwdag <sup>c</sup>
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
### Drainierende/Schallabsorbierende Deckschicht <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Draining-NoiseAbsorbingWearingLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### manto sintetico drenante <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DrainingSyntheticLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Driveable Flat Roof <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#DriveableFlatRoof`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Trockenbau <sup>c</sup>
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
### rivestimento elastico <sup>c</sup>
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
### Elevation-Foundation <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Elevation-Foundation`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Environment <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Environment`
* **Contributor(s)**
  * [cterm:FamilyOfCostComponent](https://w3id.org/cterm#FamilyOfCostComponent)
### ergotecnica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Ergonomics`
### Aushub <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Excavation`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### sistemi di scavo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExcavationSystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfTemporaryWork](https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork)
### Esecuzione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Execution`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Massetti Esistenti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExistingScreeds`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Argilla Espansa <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedClay`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Fibra Vegetale Sughero Espanso <sup>c</sup>
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
### Plastica Polietilene Espanso <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedPolyethylenePlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Plastica Polistirene Espanso (EPS) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExpandedPolystyrenePlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Exposition <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Exposure`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Exposure Class <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExposureClass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Exterior <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Exterior`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Außenflächen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ExternalSurfaces`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### External Walls <sup>c</sup>
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
### altezze di caduta <sup>c</sup>
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
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Fastenings <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fastenings`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Fences <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fences`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Ferrous Alloy Steel B450A <sup>c</sup>
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
### Filling <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Filling`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Geotessile Filtrante <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FilteringGeotextile`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Finitura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Finish`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Lana Di Abete <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FirWool`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Impianti Antincendio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireProtectionSystems`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Fire Reaction <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireReaction`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Fire Resistance <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireResistance`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Brandschutz <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireSafety`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### Antincendio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fireproof`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Brandschutztrennwand <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireproofPartition`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### controparete antincendio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FireproofPartitionWall`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Erster Anstrich <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FirstCoat`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### 5 Holes <sup>c</sup>
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
### Feste Kräne <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FixedCranes`
* **Contributor(s)**
  * [cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment)
### porta fissa <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FixedGoal`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Flat Head <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FlatHead`
* **Contributor(s)**
  * [cterm:AspectOfEquipment](https://w3id.org/cterm#AspectOfEquipment)
### Flachdach <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FlatRoof`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Flachdach mit begehbarem Belag <sup>c</sup>
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
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Bodenplatten <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FloorSlabs`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Sottopavimenti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FloorUnderlay`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Bodenbelag <sup>c</sup>
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
### Böden über unbeheizten Bereichen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FloorsOverUnheatedAreas`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### fluido <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Fluid`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Fundamente-Umgekehrte Balken-Platten <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Footings-InvertedBeams-Slabs`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Zur Realisierung von Stauwerken <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ForDamConstruction`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Für Fußball <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ForFootball`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Per Rimaneggiamento E Riutilizzo Per Variazione Della Conformazione Del Paraggio Idraulico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ForRemanipulationAndReuseForHydraulicAdjustment`
* **Contributor(s)**
  * [cterm:FunctionOfActivity](https://w3id.org/cterm#FunctionOfActivity)
### Forstwirtschaft <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Forestry`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### Forming <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Forming`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Schalungen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Formwork`
* **Contributor(s)**
  * [cterm:ObjectOfWorkOfTemporaryWork](https://w3id.org/cterm#ObjectOfWorkOfTemporaryWork)
  * [cterm:ObjectOfEquipment](https://w3id.org/cterm#ObjectOfEquipment)
### Formwork For Reinforced Concrete Structures <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FormworkForReinforcedConcreteStructures`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Schalungen für Wärmebrücken <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#FormworkForThermalBridges`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Fundament <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Foundation`
* **Contributor(s)**
  * [cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork)
### Foundation Systems <sup>c</sup>
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
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Frontale Con Porta <sup>c</sup>
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
### Galvanized <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Galvanized`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Multistrato Gas Impermeabile <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GasImpermeableMultilayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Generico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Generic`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Bitume Generico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericBitumen`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:Material](https://w3id.org/cterm#Material)
### cemento generico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericCement`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### legno artificiale generico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericEngineeredWood`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### lega ferrosa generico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericFerrousAlloy`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Generic Ferrous Alloy Steel <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericFerrousAlloySteel`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Allgemeines Material <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericMaterial`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Allgemeines Metall <sup>c</sup>
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
### Generic Natural Rock <sup>c</sup>
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
### Generic Plaster <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GenericPlaster`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Generic Rubber <sup>c</sup>
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
### Verkleben <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Gluing`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Goldgelbe Farbe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GoldenYellowColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Granular <sup>c</sup>
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
### Gray Color <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GrayColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Green <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Green`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Parks/Gardens/Green Areas <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#GreenAreas`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Green/Forest <sup>c</sup>
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
### Grout <sup>c</sup>
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
### Struktur aus Naturhartstein <sup>c</sup>
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
### Wärmereflektierend <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HeatReflective`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Height <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Height`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Helicopter Ground Assistant <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HelicopterGroundAssistant`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### elicotterista <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HelicopterPilot`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Fibra Vegetale Canapa <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HempVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Hexagonal <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Hexagonal`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### maglia esagonale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HexagonalMesh`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### High Density Rock Wool <sup>c</sup>
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
### Höhe unter Haken <sup>c</sup>
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
### Horizontal Surfaces <sup>c</sup>
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
### Hydraulic <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Hydraulic`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### Wasserbauingenieurwesen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#HydraulicEngineering`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### ad aderenza migliorata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ImprovedAdhesion`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### in blocchi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Bricks <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InBricks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### in blocchi cavi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InHollowBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Honeycomb Blocks <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InHoneycombBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Modular Panels <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InModularPanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### In Multi-Hole Blocks <sup>c</sup>
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
### in tavelle forate <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InPerforatedBricks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### in blocchi semipieni <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InSemi-SolidBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Slabs <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InSlabs`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### In Solid Blocks <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InSolidBlocks`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### in blocchi tipo svizzero <sup>c</sup>
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
### Injektion <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Injection`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Hinterland <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Inland`
* **Contributor(s)**
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### Installation <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Installation`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Isolierung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Insulation`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Dämmsysteme <sup>c</sup>
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
### Interior <sup>c</sup>
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
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Internal Partition Walls <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#InternalPartitionWalls`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Innenflächen <sup>c</sup>
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
### Iron Metal <sup>c</sup>
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
### Kitchens <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Kitchens`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Kraft Paper <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#KraftPaper`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Land <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Land`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Land/Slopes <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LandSlopes`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Verde E Paesaggio <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Landscaping`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### Posa <sup>c</sup>
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
### Stufe 1 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Level1`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### livello 2° <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Level2`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### livello 3° <sup>c</sup>
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
### Stufe C1 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelC1`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Stufe C2 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelC2`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### livello C3 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelC3`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### livello D1 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LevelD1`
* **Contributor(s)**
  * [cterm:TypeOfLabour](https://w3id.org/cterm#TypeOfLabour)
### Level D2 <sup>c</sup>
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
### Lintels <sup>c</sup>
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
### Tragend <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Load-Bearing`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Load Class <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LoadClass`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Loose Mesh <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#LooseMesh`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Manutenzione <sup>c</sup>
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
### Spietramento A Mano <sup>c</sup>
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
### Strato Di Muratura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MasonryLayer`
* **Contributor(s)**
  * [cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork)
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Matte Bronze Color <sup>c</sup>
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
### Metallstütze <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MetalProp`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### metalmeccanici <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Metalworkers`
* **Contributor(s)**
  * [cterm:CategoryOfLabour](https://w3id.org/cterm#CategoryOfLabour)
### Mineral Fiber Fir Wool <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MineralFiberFirWool`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Mineral Fiber Glass Wool <sup>c</sup>
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
### Mixed Slab with Deep Beams for Flat Structures <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#MixedSlabwithDeepBeamsforFlatStructures`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Mixing <sup>c</sup>
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
### Fibra Vegetale Sughero Biondo Naturale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#NaturalBlondCorkVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Net <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Net`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### Nominal Diameter <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#NominalDiameter`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Non-Combustible <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Non-Combustible`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Allgemeines, nicht relevantes Material <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Non-RelevantGenericMaterial`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Non-Structural <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Non-Structural`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Non Heated Attics <sup>c</sup>
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
### Normale Farbe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#NormalColor`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Olivgraue Farbe <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#OliveGrayColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### In Opera <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#OnSite`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### One Coat <sup>c</sup>
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
### Orange Color <sup>c</sup>
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
### Pannello <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Panel`
* **Contributor(s)**
  * [cterm:ObjectOfMaterial](https://w3id.org/cterm#ObjectOfMaterial)
### Panels <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Panels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
  * [cterm:AspectOfWorkOfConstructionWork](https://w3id.org/cterm#AspectOfWorkOfConstructionWork)
### Parapets for Straight Balconies in Reinforced Concrete <sup>c</sup>
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
### Teilweise sublimierend <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PartiallySubliming`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Trennwand <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Partition`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### controparete <sup>c</sup>
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
### Contropareti Con Struttura Metallica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PartitionWallsWithMetalStructure`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Passage Width <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PassageWidth`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### colore pastello <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PastelColor`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Intercapedini Perimetrali <sup>c</sup>
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
### pali <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Piles`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Säulen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Pillars`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Colore Rosa <sup>c</sup>
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
### Copertura A Falde <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PitchedRoof`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Coperture A Falde <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PitchedRoofs`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Coperture A Falde Con Tegole <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PitchedRoofsWithShingles`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Pitched Roofs With Tiles <sup>c</sup>
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
### Verputzt <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Plastered`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Stuccatura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Plastering`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### plastificata <sup>c</sup>
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
### Polyamide Material <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyamideMaterial`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Carta Kraft Politenata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyethyleneCoatedKraftPaper`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Polyethylene Plastic (PE) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyethylenePlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Polymeric Coating <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolymericCoating`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Polyolefins <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Polyolefins`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Pellicola Polipropilenica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolypropyleneFilm`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Strato Di Tessuto Non Tessuto Polipropilenico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolypropyleneNonwovenFabricLayer`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Kunststoff Polyurethanschaum (PIR) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyurethaneFoamPlastic`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### vernice poliuretanica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PolyurethanePaint`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### passerella di getto <sup>c</sup>
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
### Pre-Tensioning <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Pre-Tensioning`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Vorgefertigt <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Prefabricated`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Fertigteile für Betonstrukturen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PrefabricatedStructuresInConcrete`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Pannelli Preformati <sup>c</sup>
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
### Pressure <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Pressure`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Printed <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Printed`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Produktion <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Production`
* **Contributor(s)**
  * [cterm:FamilyOfActivity](https://w3id.org/cterm#FamilyOfActivity)
### prodotti <sup>c</sup>
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
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Provisional Elements <sup>c</sup>
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
### resistenza a punzonamento <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#PunchingResistance`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Pyramid Play Structure <sup>c</sup>
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
### Materassino Trapuntato <sup>c</sup>
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
### Pannelli A Bordi Risegati <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RebatedEdgePanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Ricostruzione <sup>c</sup>
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
### Rechteckige Pfeiler <sup>c</sup>
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
### Standardtor <sup>c</sup>
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
### Stahlbeton <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedConcrete`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Reinforced Concrete Structures <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedConcreteStructures`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Reinforced Membrane With Glass Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedMembraneWithGlassFiber`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Membrana Armata Con TNT Di Poliestere <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedMembraneWithPolyesterNonwoven`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Membrana Armata Con Velo Vetro Ardesiata <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcedSlateGlassFiberMembrane`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### rinforzo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Reinforcement`
* **Contributor(s)**
  * [cterm:ObjectOfWorkOfConstructionWork](https://w3id.org/cterm#ObjectOfWorkOfConstructionWork)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### armature e rinforzi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcementsandStrengthening`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### ferri d'armatura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ReinforcingBars`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Reinforcment <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Reinforcment`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Removal <sup>c</sup>
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
### Sostituzione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Replacement`
* **Contributor(s)**
  * [cterm:ObjectOfActivity](https://w3id.org/cterm#ObjectOfActivity)
### Residences <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Residences`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### classe di resistenza <sup>c</sup>
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
### Rhomboid Mesh <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RhomboidMesh`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Ribbed <sup>c</sup>
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
### Spigoli Ad Angolo Retto <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RightAngleCorners`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Rigid <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Rigid`
* **Contributor(s)**
  * [cterm:spectOfMaterial](https://w3id.org/cterm#spectOfMaterial)
### Pannello Rigido <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RigidPanel`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Rigid Panels <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RigidPanels`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Canali <sup>c</sup>
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
### Road Safety <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoadSafety`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Straßenbau <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoadWorks`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Roads <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Roads`
* **Contributor(s)**
  * [cterm:ObjectOfCostComponent](https://w3id.org/cterm#ObjectOfCostComponent)
### Straßenbegleitgrün <sup>c</sup>
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
### avvolgibile <sup>c</sup>
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
### Sotto Tavolati <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoofPanelling`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Coperture <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Roofing`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Roofs <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Roofs`
* **Contributor(s)**
  * [cterm:FamilyOfMaterial](https://w3id.org/cterm#FamilyOfMaterial)
### Rough <sup>c</sup>
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
### interpiano rustico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RoughFloorHeight`
* **Contributor(s)**
  * [cterm:DimensionParameterType](https://w3id.org/cterm#DimensionParameterType)
### Rau ohne Beschichtung <sup>c</sup>
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
### Gummibodenbelag <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#RubberFlooring`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### sabbiato <sup>c</sup>
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
### Estrich <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Screeds`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Seams <sup>c</sup>
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
### Pannelli Autoportanti <sup>c</sup>
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
### Halbsteife Platte <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Semi-RigidPanel`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### apprestamenti <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Setups`
* **Contributor(s)**
  * [cterm:FamilyOfEquipment](https://w3id.org/cterm#FamilyOfEquipment)
### Condotte/Fogna/Acquedotto <sup>c</sup>
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
### Seitenverschluss <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SideClosure`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Gehwege <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Sidewalks`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### struttura in conglomerato cementizio semplice <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SimpleConcreteStructure`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Site Setup Systems <sup>c</sup>
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
### Slaked Lime <sup>c</sup>
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
### Glatt <sup>c</sup>
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
### Smoothed on Glass <sup>c</sup>
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
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
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
### Solid Brick-Stone-Mixed Masonry <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SolidBrick-Stone-MixedMasonry`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### solai e solette piene in c.a. con travi a spessore <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SolidSlabsandFloorsinReinforcedConcretewithDeepBeams`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Schalldämpfend <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SoundAbsorbing`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Schallabsorption <sup>c</sup>
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
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
### Special Mortars (Rubber Granules, Polyurethane Resins, etc.) <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpecialMortars`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
### Facharbeiter <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Specialized`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### specializzato super <sup>c</sup>
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
### tecnico specialistico per lavorazioni ICT <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpecializedTechnicianforICTWork`
* **Contributor(s)**
  * [cterm:QualificationLevel](https://w3id.org/cterm#QualificationLevel)
### Spezifisches Gewicht <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SpecificWeight`
* **Contributor(s)**
  * [cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType)
### attrezzature sport <sup>c</sup>
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
### A Spruzzo <sup>c</sup>
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
### Quadratisches Netz <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SquareMesh`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Stabilisierte Bodenbeläge <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StabilizedEarthCarpets`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### inox <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Stainless`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Edelstahllegierung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StainlessSteelAlloy`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Edelstahllegierung AISI 304 <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StainlessSteelAlloyAISI304`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Stainless Steel Alloy AISI 304l <sup>c</sup>
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
### Staircase-Elevator Shaft Walls <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Staircase-ElevatorShaftWalls`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### cucitura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Stitching`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Stone Removal <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StoneRemoval`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Straight-Curved Axis <sup>c</sup>
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
### pianerottoli e rampe scale rettilinei <sup>c</sup>
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
### Litze <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Strand`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### Litzen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Strands`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Stringcourses <sup>c</sup>
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
### Structural Engineering <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#StructuralEngineering`
* **Contributor(s)**
  * [cterm:FamilyOfWork](https://w3id.org/cterm#FamilyOfWork)
### Strukturelle Verstärkung <sup>c</sup>
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
### sottofondazione <sup>c</sup>
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
### Synthetic Acrylic Resin <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SyntheticAcrylicResin`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### conglomerato sintetico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SyntheticCompound`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### gomma sintetica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#SyntheticRubber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### sistemi <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Systems`
* **Contributor(s)**
  * [cterm:CategoryOfMaterial](https://w3id.org/cterm#CategoryOfMaterial)
### T-Kopf <sup>c</sup>
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
### recinzioni provvisorie <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TemporaryFences`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Zugfestigkeit <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TensileStrength`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Resistenza A Trazione Perpendicolare Alle Facce <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TensileStrengthPerpendicularToFaces`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Abspannung <sup>c</sup>
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
### Terrassen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Terraces`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Thermal <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Thermal`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Wärmebrücken <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalBridges`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Conducibilità Termica <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalConductivity`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Thermal Insulating <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalInsulating`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### Thermal Insulating and Sound Absorbing Partition Wall <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalInsulatingandSoundAbsorbingPartitionWall`
* **Contributor(s)**
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Isolamento Termico <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#ThermalInsulation`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### resistenza termica <sup>c</sup>
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
### spessore <sup>c</sup>
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
### Dreidimensionales Geflechtseil <sup>c</sup>
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
### Oben drehender Turmkran <sup>c</sup>
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
### Turmdrehkran an der Oberseite <sup>c</sup>
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
### Traditional <sup>c</sup>
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
### Truck with Crane <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TruckwithCrane`
* **Contributor(s)**
  * [cterm:TypeOfEquipment](https://w3id.org/cterm#TypeOfEquipment)
### Fachwerk <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Truss`
* **Contributor(s)**
  * [cterm:TypeOfWorkOfConstructionWork](https://w3id.org/cterm#TypeOfWorkOfConstructionWork)
### Due Mani <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TwoCoats`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Due Riprese <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#TwoLayers`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Unterfangungen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Underpinnings`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Urban Green <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#UrbanGreen`
* **Contributor(s)**
  * [cterm:CategoryOfCostComponent](https://w3id.org/cterm#CategoryOfCostComponent)
### Verschiedene Strukturen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VariousStructures`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Formazione Vespai Aerati <sup>c</sup>
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
### Belüftetes Pultdach <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#VentilatedPitchedRoof`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Belüftung <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Ventilation`
* **Contributor(s)**
  * [cterm:FunctionOfMateriaResource](https://w3id.org/cterm#FunctionOfMateriaResource)
  * [cterm:FunctionOfWorkOfConstructionWork](https://w3id.org/cterm#FunctionOfWorkOfConstructionWork)
### Vertical Structures <sup>c</sup>
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
### Fibra Minerale Lana Di Roccia Vulcanizzata <sup>c</sup>
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
### Walkable Attics <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WalkableAttics`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### parete-soffitto <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Wall-Ceiling`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Wall Systems <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WallSystems`
* **Contributor(s)**
  * [cterm:CategoryOfWorkOfTemporaryWork](https://w3id.org/cterm#CategoryOfWorkOfTemporaryWork)
### Walls <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Walls`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Walls With Insulated Plaster System <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WallsWithInsulatedPlasterSystem`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Wände für Treppen- und Aufzugsschächte <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WallsforStaircasesandElevators`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### pareti in elevazione <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WallsinElevation`
* **Contributor(s)**
  * [cterm:UseOfEquipment](https://w3id.org/cterm#UseOfEquipment)
  * [cterm:UseOfWorkOfTemporaryWork](https://w3id.org/cterm#UseOfWorkOfTemporaryWork)
### Wasserabweisend <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WaterRepellent`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Resistenza Alla Diffusione Del Vapore Acqueo <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WaterVaporDiffusionResistance`
* **Contributor(s)**
  * [cterm:PerformanceParameterType](https://w3id.org/cterm#PerformanceParameterType)
### Waterproof <sup>c</sup>
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
### Gewellt <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Wavy`
* **Contributor(s)**
  * [cterm:AspectOfMaterial](https://w3id.org/cterm#AspectOfMaterial)
### Verschleißfest <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Wear-Resistant`
* **Contributor(s)**
  * [cterm:FunctionOfMaterial](https://w3id.org/cterm#FunctionOfMaterial)
### strato di usura <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WearingLayer`
* **Contributor(s)**
  * [cterm:UseOfMaterial](https://w3id.org/cterm#UseOfMaterial)
### Gewicht <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Weight`
* **Contributor(s)**
  * [cterm:PhysicalParameterType](https://w3id.org/cterm#PhysicalParameterType)
### Welded <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Welded`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### White <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#White`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Colore Bianco <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WhiteColor`
* **Contributor(s)**
  * [cterm:FinishingOfMaterial](https://w3id.org/cterm#FinishingOfMaterial)
### Width <sup>c</sup>
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
### Wire <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#Wire`
* **Contributor(s)**
  * [cterm:TypeOfMaterial](https://w3id.org/cterm#TypeOfMaterial)
### con gru <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WithCrane`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### With Manual Equipment <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WithManualEquipment`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Con Mezzo Meccanico E Manuale <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WithMechanicalAndManualMeans`
* **Contributor(s)**
  * [cterm:TypeOfActivity](https://w3id.org/cterm#TypeOfActivity)
### Mit Mechanischen Mitteln <sup>c</sup>
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
### Wood Vegetable Fiber <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WoodVegetableFiber`
* **Contributor(s)**
  * [cterm:Material](https://w3id.org/cterm#Material)
### Lana Di Legno <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WoodWool`
* **Contributor(s)**
  * [cterm:FinishingOfWorkOfConstructionWork](https://w3id.org/cterm#FinishingOfWorkOfConstructionWork)
### Holzstrukturen <sup>c</sup>
Property | Value
--- | ---
IRI | `https://w3id.org/cterm#WoodenStructures`
* **Contributor(s)**
  * [cterm:UseOfWorkOfConstructionWork](https://w3id.org/cterm#UseOfWorkOfConstructionWork)
### Worker <sup>c</sup>
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