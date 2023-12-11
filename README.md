# Eventful
Eventful is a framework for naming calendar events.

## Formatting

Eventful uses four main values: `activity`, `location`, `topics`, and `participants`. 

Two types of separators are added to enhance readability: `activity` values are separated from `location`, `topics`, and `participants` with a **colon**, whereas `location`, `topics`, and `participants` values are separated with a **hyphen**.

```
[Activity]: [Topic] - [Location] - [Pariticipants]
```

Certain values may be omitted from the title, insofar as they are needed to provide appropriate context. For example, it may be sufficient to mention only the event location or topic. In that case, the activity value may be dropped. The purpose is to strike a balance between brevity and clarity of the event title.

## Principles

* Follow [title case](https://en.wikipedia.org/wiki/Title_case) formatting rules i.e., capitalize the first letter of each significant word in the event title.
* List pariticipants in alphabetical order.
* Avoid using special characters to simplify editing on the go (but ampersands are allowed).
* Avoid using abbreviations, acronyms, or technical jargon unless they are widely understood.

## Examples

```
Phill’s Coffee - Bruce & Selina 
Event Planning - Phill’s Coffee - Bruce & Selina
```
```
Product Design - Bruce & Selina
Marketing Strategy - Bruce & Selina
```
```
Workshop: Marketing Strategy - WeWork Market St - Executive Team
Off-site: Marketing Strategy - Farallon Islands - Executive Team
```
```
Intro: Bruce & Selina
Intro: Bruce & Team
```
```
Walk: Golden Gate Park - Bruce & Selina
Picnic: Golden Gate Park - Bruce & Selina
```
```
Drive: San Francisco - San Jose
Train: San Francisco - San Jose
Flight: San Francisco - San Diego
```

## License

Eventful is available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Please link back to the source when you share and / or adapt any of the contents.
