# gpt-3-experiments

A repo containing Python scripts to automate generation from OpenAI's GPT-3 based API

**Disclaimer: generated content in this repository may be offensive. The READMEs of the corresponding examples will include an explicit content warning when this is the case.**

Because GPT-3 favors few-shot learning, the input prompts must be longer and more semantically structured than tiny prompts often used with GPT-2. (but we will still need to test both)

# Repo Layout

This repo contains folders for each prompt example in the `/examples` folder.

The README for each prompt example contains the input, the output at `temperature=0.0` (i.e. the model will always choose the most likely output and is therefore deterministic), and any content warnings as noted above.

## Usage

The script requires the installation of certain common Python packages:

```sh
pip3 install requests pyyaml fire tqdm
```

## Maintainer/Creator

Max Woolf ([@minimaxir](https://minimaxir.com))

_Max's open-source projects are supported by his [Patreon](https://www.patreon.com/minimaxir) and [GitHub Sponsors](https://github.com/sponsors/minimaxir). If you found this project helpful, any monetary contributions to the Patreon are appreciated and will be put to good creative use._

## License

MIT