# Changelog

## [0.9.3](https://github.com/giuseppe-steduto/reana/compare/v0.9.2...0.9.3) (2024-01-24)


### Bug fixes

* **reana-dev:** delete extra files with git-submodule --update ([#764](https://github.com/giuseppe-steduto/reana/issues/764)) ([e5680ce](https://github.com/giuseppe-steduto/reana/commit/e5680ce8bd1a9f80dde4ca448f9fc8d21aa1c6ca))


### Performance improvements

* add locust performance stress tests ([5e5266f](https://github.com/giuseppe-steduto/reana/commit/5e5266f69dbd719f943a1b2b74a2f4432c781a35))


### Continuous integration

* added flake8 linter ([86e1c8b](https://github.com/giuseppe-steduto/reana/commit/86e1c8baf63386e9dec216bccfe6a419b99dacca))
* added github actions workflow ([4c4ee23](https://github.com/giuseppe-steduto/reana/commit/4c4ee2387060f6c11e537dd76cafea4a04cd814c))
* **commitlint:** addition of commit message linter ([#767](https://github.com/giuseppe-steduto/reana/issues/767)) ([be77666](https://github.com/giuseppe-steduto/reana/commit/be77666bb80601c0211674a59a3f91d2609712f9))
* pin ubuntu version in GA jobs ([570cc1c](https://github.com/giuseppe-steduto/reana/commit/570cc1cd3255ef63a3eaacfc7a9b1ac7aa793c77))
* **release-please:** initial configuration ([#767](https://github.com/giuseppe-steduto/reana/issues/767)) ([bb45539](https://github.com/giuseppe-steduto/reana/commit/bb455393ac1b4d149cfef4df6e96ae730c25501c))
* **release-please:** update version in Helm Chart ([#770](https://github.com/giuseppe-steduto/reana/issues/770)) ([09c9210](https://github.com/giuseppe-steduto/reana/commit/09c9210d68e29d094c0e76a4002b17a21fcda701))
* update all actions ([e59b982](https://github.com/giuseppe-steduto/reana/commit/e59b98288b2d98855ca1ef9bd05d5d3af483b419))


### Documentation

* add .readthedocs.yaml to migrate to RTD v2 ([5706804](https://github.com/giuseppe-steduto/reana/commit/5706804d1886711ac4c686d6dac2d3fe1aa2affe))
* add port forwarding info to dev guide ([0808fe3](https://github.com/giuseppe-steduto/reana/commit/0808fe3a4c18a40efb1bd1f3262cf95b3e724507))
* add prerequisites link for minikube ([9ada804](https://github.com/giuseppe-steduto/reana/commit/9ada804cdc9789fe985b0e09b27ccac1427cfd06))
* adds documentation for comupute backends ([9ad8ad4](https://github.com/giuseppe-steduto/reana/commit/9ad8ad4b9b88b5b41ef6e052299cf9aeb59f4c0d))
* adds krb5s example ([ba7b115](https://github.com/giuseppe-steduto/reana/commit/ba7b115231e54ec12b54d0a99ea52e8332abe345))
* airy panel ([c9bc1ca](https://github.com/giuseppe-steduto/reana/commit/c9bc1ca32df131b1b10efcee32cf75c4464ea313))
* amend wdb URL retrieval process ([51a9d3c](https://github.com/giuseppe-steduto/reana/commit/51a9d3c670eef8b2b0f01f61004aa4affb56fb44))
* author ORCID links ([8df3ae6](https://github.com/giuseppe-steduto/reana/commit/8df3ae64b0154c8b9ce7f96d3d6ef75e28051e35))
* corrected spelling mistake in flag ([1484881](https://github.com/giuseppe-steduto/reana/commit/14848812e75d26d38e290a709d5641b1b79c4629))
* CVMFS usage instructions ([2059020](https://github.com/giuseppe-steduto/reana/commit/205902076702e42ae609f7db4214803ceefb23b9))
* docker-build -t latest ([ae6d761](https://github.com/giuseppe-steduto/reana/commit/ae6d761d8f121100225558e17aa7c26ca1888682))
* downgrade urllib3 ([37b9f2d](https://github.com/giuseppe-steduto/reana/commit/37b9f2d76242b471ba5cf92d15d56f47e83bcccf))
* fix deployment links ([d2b16b2](https://github.com/giuseppe-steduto/reana/commit/d2b16b2dced2a7fcbdff013f0491cc84b4834a0e))
* fix Twitter link ([2caa444](https://github.com/giuseppe-steduto/reana/commit/2caa4442418e42ac01bc115c1b5e8d1d6173cb1b))
* fixed small typo ([99a41d4](https://github.com/giuseppe-steduto/reana/commit/99a41d46f0e2caf507a78aa2c554932526f3c49e))
* general update for v0.2.0 release ([a7be535](https://github.com/giuseppe-steduto/reana/commit/a7be535be298f3ec3d6bd094af5d0290722a3a9b))
* improve debugging section ([1d544be](https://github.com/giuseppe-steduto/reana/commit/1d544beae48b0707a95de91fb06c993d2690ef11)), closes [#212](https://github.com/giuseppe-steduto/reana/issues/212)
* krb5 fix ([eb19894](https://github.com/giuseppe-steduto/reana/commit/eb1989440901c426f37999f44e939d2c370be954))
* mention interactive session in user guide ([5673e4f](https://github.com/giuseppe-steduto/reana/commit/5673e4fa7143ef11b77977be81f3ad2ad6315739))
* minikube/0.35 kubectl/1.13.4 ([61501e8](https://github.com/giuseppe-steduto/reana/commit/61501e8907232961edf043035c35667e586c2a87))
* move releasing docs to docs.reana.io ([080898f](https://github.com/giuseppe-steduto/reana/commit/080898ffc13a1edf3d0d3ec7c7e9599c53bbf369))
* move to docs.reana.io enrich README ([9abd6ff](https://github.com/giuseppe-steduto/reana/commit/9abd6ffe94008020173de153786adb8039d2de44))
* new contributor ([8e08207](https://github.com/giuseppe-steduto/reana/commit/8e08207ca17c5964a6b205a7e4491552f65dc51b))
* new logo and better verbiage ([282e8f5](https://github.com/giuseppe-steduto/reana/commit/282e8f515226917bcc4bdebb9ee64c8a041f3cfb))
* rename reana-pytest-commons to pytest-reana ([d8d7c9b](https://github.com/giuseppe-steduto/reana/commit/d8d7c9be9844b8767cac6558cb73fa1588950f94))
* revert deletion of docs/requirements.txt ([c4912ec](https://github.com/giuseppe-steduto/reana/commit/c4912ec0e8af241250ffcacc57dcf85cd6505497))
* richer user guide ([b44a9bb](https://github.com/giuseppe-steduto/reana/commit/b44a9bb45a8ef6fc68bdae1445bf643b8c68e863))
* set default language to English ([ff110ba](https://github.com/giuseppe-steduto/reana/commit/ff110ba72e8cc76fad44c8df241e956b5126a685))
* supporting non-root users ([2a5f127](https://github.com/giuseppe-steduto/reana/commit/2a5f12733d49095ad55369e7fd915b5dac1fda58))
* update changelog ([c65f9c9](https://github.com/giuseppe-steduto/reana/commit/c65f9c90061477423dc3eb897a274c43a42002ef))
* update deployment config file name ([32126dc](https://github.com/giuseppe-steduto/reana/commit/32126dce77a6288820c5c1e8e6a8b4fab9198835))
* update to latest reana-client usage ([5bc9b3b](https://github.com/giuseppe-steduto/reana/commit/5bc9b3ba7210fe45f15bd1d031cb3b83666f80fb))
* upgrade compatible k8s and minikube versions ([86d2e81](https://github.com/giuseppe-steduto/reana/commit/86d2e8131d8bb3f1126dcc8569193a385227a575))
* upgrading kubernetes version ([d68e970](https://github.com/giuseppe-steduto/reana/commit/d68e970807ffaccd6e73d37fe7d56a561764a3bc))
