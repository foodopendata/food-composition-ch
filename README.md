The Swiss Food Composition Database contains information on the composition of foods that are available in Switzerland. The data set contains approximately 10,500 foods that have been classified into 19 main and 105 sub categories. 

The database is operated by the [Federal Food Safety and Veterinary Office](https://www.blv.admin.ch/blv/en/home.html).

Sources:

- [naehrwertdaten.ch](http://www.naehrwertdaten.ch/)

## Schema

These are available in two separate collections of generic (`generic-foods.csv`) and branded (`branded-foods.csv`) foods.

Columns in the schema:
```
ID,ID V 4.0,ID SwissFIR,name D,synonyms D,name F,synonyms F,name I,synonyms I,name E,synonyms E,category D,category F,category I,category E,specific gravity,energy kJ,unit,matrix unit,value type,source,energy kcal,unit,matrix unit,value type,source,protein,unit,matrix unit,value type,source,alcohol,unit,matrix unit,value type,source,water,unit,matrix unit,value type,source,carbohydrates, available,unit,matrix unit,value type,source,starch,unit,matrix unit,value type,source,sugars,unit,matrix unit,value type,source,dietary fibres,unit,matrix unit,value type,source,fat, total,unit,matrix unit,value type,source,cholesterol,unit,matrix unit,value type,source,fatty acids, monounsaturated,unit,matrix unit,value type,source,fatty acids, saturated,unit,matrix unit,value type,source,fatty acids, polyunsaturated,unit,matrix unit,value type,source,vitamin A activity,unit,matrix unit,value type,source,all-trans retinol equivalents,unit,matrix unit,value type,source,beta-carotene activity,unit,matrix unit,value type,source,beta-carotene,unit,matrix unit,value type,source,vitamin B1 (thiamine),unit,matrix unit,value type,source,vitamin B2 (riboflavin),unit,matrix unit,value type,source,vitamin B6 (pyridoxine),unit,matrix unit,value type,source,vitamin B12 (cobalamin),unit,matrix unit,value type,source,niacin,unit,matrix unit,value type,source,folate,unit,matrix unit,value type,source,pantothenic acid,unit,matrix unit,value type,source,vitamin C (ascorbic acid),unit,matrix unit,value type,source,vitamin D (calciferol),unit,matrix unit,value type,source,vitamin E activity,unit,matrix unit,value type,source,sodium (Na),unit,matrix unit,value type,source,potassium (K),unit,matrix unit,value type,source,chloride (Cl),unit,matrix unit,value type,source,calcium (Ca),unit,matrix unit,value type,source,magnesium (Mg),unit,matrix unit,value type,source,phosphorus (P),unit,matrix unit,value type,source,iron (Fe),unit,matrix unit,value type,source,iodide (I),unit,matrix unit,value type,source,zinc (Zn),unit,matrix unit,value type,source,record has changed
```

## License

This package is licensed by its maintainers under the Public Domain Dedication
and License.

Data is republished here in view of the original [terms of use](http://www.naehrwertdaten.ch/request?xml=MessageData&xml=MetaData&xsl=Information&lan=en&pageKey=Start):

> The FSVO provides the data free of charge to all interested parties. The data may be used, also for commercial purposes, (e.g. integration into food composition calculation software or nutrition diary-app) and scientific purposes, subject to acknowledgment of the source.

Nevertheless, it should be noted that this material is currently sourced from
several third-parties whose data publishing rights and licensing policies are somewhat
unclear.

If you intended to use these data in a public or commercial product, please
check the original sources for any specific restrictions.
