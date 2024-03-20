# Kudos Medals

Portable and immutable rewards and acknowledgements.

- [Sample Collection](#sample-collection)
- [Samples with details](#samples-with-details)
- [Type Schema](#type-schema)
- [References](#ref)

## Sample Collection
|                                                                     |                                                                       |                                                                        |                                                                       |                                                                       |                                                                       |
|---------------------------------------------------------------------|-----------------------------------------------------------------------|------------------------------------------------------------------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------|
| <img alt="Sample medal" src="/src/composites/manual/composite.svg"> | <img alt="Sample medal" src="/src/composites/manual/composite_2.svg"> | <img alt="Sample medal" src="/src/composites/manual/composite_3_.svg"> | <img alt="Sample medal" src="/src/composites/manual/composite_4.svg"> | <img alt="Sample medal" src="/src/composites/manual/composite_5.svg"> | <img alt="Sample medal" src="/src/composites/manual/composite_6.svg"> |


## Samples with details
| Type                                                                   | Image                                       | Data                                                             |
|------------------------------------------------------------------------|---------------------------------------------|------------------------------------------------------------------|
| <img alt="Sample medal" src="/src/composites/manual/composite.svg">    | **medal:status:crew:ui_polishers**          | [metadata json](metadata/medal.status.crew.ui_polishers.json)    |
| <img alt="Sample medal" src="/src/composites/manual/composite_2.svg">  | **medal:status:crew:perf**                  | [metadata json](metadata/medal.status.crew.perf.json)            |
| <img alt="Sample medal" src="/src/composites/manual/composite_3_.svg"> | **medal:status:anniversary:6**              | [metadata json](metadata/medal.status.anniversary.6.json)        |
| <img alt="Sample medal" src="/src/composites/manual/composite_4.svg">  | **medal:logos:anniversary:6**               | [metadata json](metadata/medal.logos.anniversary.6.json)         |
| <img alt="Sample medal" src="/src/composites/manual/composite_5.svg">  | **medal:status:anniversary:1**              | [metadata json](metadata/medal.status.anniversary.1.json)        |
| <img alt="Sample medal" src="/src/composites/manual/composite_6.svg">  | **medal:status:crew_captain:ui_polishers**  | [metadata json](metadata/medal.status.captain.ui_polishers.json) |

## Type Schema

The following is an example of a reward type:

`medal:status:anniversary:6`

This type identifier follows the below schema

`<AWARD_TYPE>:<PROJECT_NAME>:<AWARD_SUBTYPE>:<AWARD_SUBTYPE_DATA>`

| Type                 | Description                                                                 | Type examples                        |
|----------------------|-----------------------------------------------------------------------------|--------------------------------------|
| `AWARD_TYPE`         | The type of award given, this give context to the underlying award          | `medal`, `certificate`, `trophy`     |
| `PROJECT_NAME`       | The project that has issued the award                                       | `status`, `waku`, `logos`            |
| `AWARD_SUBTYPE`      | Describes what the award is for. Example a `medal` for a work `anniversary` | `anniversary`, `crew`, `captainhood` |
| `AWARD_SUBTYPE_DATA` | Data about the subtype                                                      | `perf`, `6`                          |

## Ref

https://github.com/ethereum/ercs/blob/master/ERCS/erc-1155.md