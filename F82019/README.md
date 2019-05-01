# F8 2019

## FB with React

* React
* GraphQL
* Relay (manage fetching data - only necessary (?!))

Critical content fetch first, without waiting to render to display.

Lazy fetching - Download unnecessary resources (data/code), making slower.

GraphQL
* describe the model type
* describe the data type

Code spliting

React.lazy

How to send the right code for first loading?

Data-driven code-spliting.

1. Loading screen blank skeleton
2. content display
3. Interactive

Defer AfterLoad()

* Server rendering
* Code size budget - design for performance (size)

JS Graph Explorer
* measure code.

* atomic stylesheets

React.Suspense
isInputPending => cancels javascript execution and responds to a new action.
CSS variables.

px - static
em - relative, but composing, so multiple
rem - relative to the root.

Contextual heading
* highlights in different contexts.

## React Native

* Can I make a app's subsection with React Native and use inside the native one?

* quick iteration
* re-usable components.

* know the platform => knowing what's the expectation is for native
* native is richer than web

Making network/server requests as early as possible (in parallel with code);

Componentkit
Litho

https://componentkit.org/
https://fblitho.com/

Internationalization: https://facebookincubator.github.io/fbt/

## Speach and Audio

Benefits of audio transcript
* accessibility
* watching without audio
* relevance / ranking
* avoid negative / hate speach

Acoustic Model = sounds pronunciation
Pronunciation Dictionary = language / words
Language model = phrases

Training data => just train sounds to words and phrases, skip the sound (acustic) model to pronunciations.

https://github.com/facebookresearch/wav2letter

Training using simulations

Choosing right person by pattern recognition.

Names are harder to understand. Regional characteristics.

Text to Speach (TTS) - obtain personal audio

## FBT

https://facebookincubator.github.io/fbt/
https://github.com/facebookincubator/fbt

```
<fbt:pronoun type="possessive" gender={} human="true">
```

https://facebookincubator.github.io/fbt/docs/pronouns

## React Hooks

https://codesandbox.io/s/lyo8z1yw7


