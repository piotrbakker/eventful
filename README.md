# Eventz
Eventz is a framework for naming calendar events.

## Formatting

Eventz divides event titles into four main elements: `activity`, `location`, `topics`, and `participants`. 

The primary `activity` in the event title is set apart from `location`, `topics`, and `participants` with a colon, whereas `location`, `topics`, and `participants` are separated with a hyphen.

```
[Activity]: [Location] - [Topic] - [Pariticipants]
```

Note: each element should be used with restraint, insofar as it is needed to provide appropriate context. For example, it can be self-evident what the primary activity is from either the event location or topic.

## Core principles

* Use title case capitalization i.e., capitalize the first letter of each significant word in the event title.
* When listing pariticipants start with event host.
* Avoid using special characters to simplify editing on the go.
* Avoid using abbreviations, acronyms, or technical jargon unless they are widely understood.

## Examples

```
Phill’s Coffee - Bruce & Selina
Phill’s Coffee - Event Planning - Bruce & Selina
```
```
Product Design - Bruce & Selina
Marketing Strategy - Bruce & Selina
```
```
Workshop: WeWork Market St - Marketing Strategy - Executive Team
Off-site: Farallon Islands - Marketing Strategy - Executive Team
```
```
Intro: Bruce & Selina
Intro: Bruce & Team
```
```
Walk: Golden Gate Park - Bruce & Selina
Picknic: Golden Gate Park - Bruce & Selina
```
```
Drive: San Francisco - San Jose
Train: San Francisco - San Jose
Flight: San Francisco - San Diego
```

## License

Eventz is available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/). Please link back to the source when you share and / or adapt any of the contents.
