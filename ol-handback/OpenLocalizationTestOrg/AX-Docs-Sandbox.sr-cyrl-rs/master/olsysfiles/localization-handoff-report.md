# <a name='report-top'></a> Localization Handoff Report

## Summary
 Total Files | 2

## File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [dev-itpro\user-interface\data-validation-workspace.md](https://github.com/OpenLocalizationTestOrg/AX-Docs-Sandbox/blob/baf4250b63125107a798b55e52e7d06e177bba2e/dev-itpro/user-interface/data-validation-workspace.md) | HandedOffFailed | [Details](#13370d89f1894b7fb496144776295f427defbced2164)
 [retail\dev-itpro\hardware-station-extensibility.md](https://github.com/OpenLocalizationTestOrg/AX-Docs-Sandbox/blob/7a8ce2c15a4e80e74cce9415bd10c3171906bc1d/retail/dev-itpro/hardware-station-extensibility.md) | HandedOffFailed | [Details](#b9f109aca4f3580306ac130a2cc100f956feea743367)

## Item Details
##### <a name='13370d89f1894b7fb496144776295f427defbced2164'></a> Source: [dev-itpro\user-interface\data-validation-workspace.md](https://github.com/OpenLocalizationTestOrg/AX-Docs-Sandbox/blob/baf4250b63125107a798b55e52e7d06e177bba2e/dev-itpro/user-interface/data-validation-workspace.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 2017-06-15 14:42:11
* Handoff Reason: Ignored
* Handoff Name: 
* Handoff Error: [handoff_transform_failed](#13370d89f1894b7fb496144776295f427defbced2164handoff_transform_failed)
* Archive File: 
* Archive Datetime: 0001-01-01 00:00:00
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* Handback Name: 
* [Back to Top](#report-top)

##### <a name='b9f109aca4f3580306ac130a2cc100f956feea743367'></a> Source: [retail\dev-itpro\hardware-station-extensibility.md](https://github.com/OpenLocalizationTestOrg/AX-Docs-Sandbox/blob/7a8ce2c15a4e80e74cce9415bd10c3171906bc1d/retail/dev-itpro/hardware-station-extensibility.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 2017-06-15 14:42:11
* Handoff Reason: Ignored
* Handoff Name: 
* Handoff Error: [handoff_transform_failed](#b9f109aca4f3580306ac130a2cc100f956feea743367handoff_transform_failed)
* Archive File: 
* Archive Datetime: 0001-01-01 00:00:00
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* Handback Name: 
* [Back to Top](#report-top)


## Error Details
##### <a name='13370d89f1894b7fb496144776295f427defbced2164handoff_transform_failed'></a> Source: [dev-itpro\user-interface\data-validation-workspace.md](#13370d89f1894b7fb496144776295f427defbced2164)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: dev-itpro\user-interface\data-validation-workspace.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: dev-itpro\\user-interface\\data-validation-workspace.md transformed failed.","internal_error_retriable":false,"exception_message":"Unable to convert markdown with invalid metadata: Invalid yaml header when parsing:\n# required metadata\n\ntitle: Data validation workspace\ndescription: The Data validation checklist workspace lets you track data validation processes across companies, areas, and people. \nThe checklist can be used during a new implementation, after an upgrade, or after a migration.\nauthor: bking\nmanager: AnnBe\nms.date: 05/11/2017\nms.topic: article\nms.prod: \nms.service: Dynamics365Operations\nms.technology: \n\n# optional metadata\n\n# ms.search.form:  \naudience: Application User\n# ms.devlang: \n# ms.reviewer: twheeloc\n# ms.search.scope: \n# ms.tgt_pltfrm: \n# ms.custom: \nms.assetid: \nms.search.region: Global \n# ms.search.industry: \nms.author: bking\nError message: (Line: 6, Col: 1, Idx: 281) - (Line: 6, Col: 1, Idx: 281): While scanning a simple key, could not find expected ':'.","exception_type":"System.IO.InvalidDataException","stack_trace":"   at Microsoft.OpenLocalization.Transformer.TransformerClient.MarkdownToXliff(Stream sourceStream, Stream xliffStream, Stream skeletonStream, String srcLocale, String targetLocale, String xliffVersion, IReadOnlyDictionary`2 options) in C:\\Jenkins\\workspace\\OpenLocalization-Sandbox\\src\\OpenLocalization.Transformer.Core\\TransformerClient.cs:line 84\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.MarkdownToXliff(String mdfile, String xliffFile, String skeletonFile, String sourceLocale, String targetLocale, String xliffVersion, IReadOnlyDictionary`2 transformerOptions) in C:\\Jenkins\\workspace\\OpenLocalization-Sandbox\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 59\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.<>c__DisplayClass28_0.<CreateHandoffFiles>b__0(Tuple`5 handoff) in C:\\Jenkins\\workspace\\OpenLocalization-Sandbox\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 295","extended_information":null}

##### <a name='b9f109aca4f3580306ac130a2cc100f956feea743367handoff_transform_failed'></a> Source: [retail\dev-itpro\hardware-station-extensibility.md](#b9f109aca4f3580306ac130a2cc100f956feea743367)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: retail\dev-itpro\hardware-station-extensibility.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: retail\\dev-itpro\\hardware-station-extensibility.md transformed failed.","internal_error_retriable":false,"exception_message":"retail\\dev-itpro\\hardware-station-extensibility.md file with commit id 7a8ce2c15a4e80e74cce9415bd10c3171906bc1d can not be found","exception_type":"System.IO.FileNotFoundException","stack_trace":"   at Microsoft.OpenLocalization.Localization.LocalizationCore.<>c__DisplayClass28_0.<CreateHandoffFiles>b__0(Tuple`5 handoff) in C:\\Jenkins\\workspace\\OpenLocalization-Sandbox\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 276","extended_information":null}


Generated by OpenLocalization.
