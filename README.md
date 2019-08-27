# Shadowizard

This repo is based on the DesignCourse's *shadowizard* youtube video, which is a guide on learning how to create and publish an NPM package.
If you're interested in learning, please visit [https://www.youtube.com/watch?v=4zzbNac6f6Q](https://www.youtube.com/watch?v=4zzbNac6f6Q)


## Installation

`npm i shadowizard-greg --save`

## Usage

```
import { shadowizard } from 'shadowizard-greg'

shadowizard({
    shadow_type: 'soft',
    padding: false
})
```

## Options 
* *shadow_type* - _hard | soft_ (defaults to soft)
* *padding* - _boolean_
