<p align="center"><img width="200" src="logo.jpg" alt="Tiny Machine Learning Company"></p>


Hey, this is TMLC and these are our products we're working on

## TMLC AutoML

You don't need to learn how to build artificial intelligence models anymore

### Just upload your data and get an AI model

[Click here to sign up on a priority waitlist and get an early access to the platform](https://mailchi.mp/1f414e9e32d1/t06qvxkc5z)

It's under construction, but you can preview how it's going to work:

Interfaces:
- Web application: [automl.tmlc.pl](https://automl.tmlc.pl)
- API:

(Example)
```ts
import automl from "@tmlc/automl";

const model = automl.train(API_KEY, DATA_PATH);
model.predict(NEW_DATA_PATH);
```

## TMLC OpenAI Polling

A library that [fills the gaps in OpenAI Threads API](https://platform.openai.com/docs/assistants/how-it-works/polling-for-updates)

Install:
```bash
npm install @tmlc/openai-polling
```

Usage:
```ts
import { poll } from '@tmlc/openai-polling';

await poll(openai, thread, run);
```

## About us
> A humble research and development in machine learning, space engineering and robotics conducted at home with coffee, lofi and intrinsic curiosity

Company blog: [https://tmlc.substack.com/](https://tmlc.substack.com/) (it's still quite empty, but feel free to subscribe to not miss the new posts)

TMLC Poland 2024
