# Changelog

## [0.10.0](https://github.com/mian196/google_photos_mobile_client/compare/v0.9.0...v0.10.0) (2026-08-10)


### Features

* --album `AUTO` ([0db3348](https://github.com/mian196/google_photos_mobile_client/commit/0db3348f070d5271666953b80c3dc8e651d7bb9c))
* `--use-quota` and `--saver` cli args ([fdb0795](https://github.com/mian196/google_photos_mobile_client/commit/fdb0795bc3d571f3cef2eb3b08221fbf06820dd4))
* `add_to_album` improvements ([61b651f](https://github.com/mian196/google_photos_mobile_client/commit/61b651f551c4379ad06faf2dad5fb0fbadd3a016))
* `move_to_trash` method ([cb402a3](https://github.com/mian196/google_photos_mobile_client/commit/cb402a3e2b196651d67f9cbce8b87e78c518689c))
* add --album-id to upload into an existing album ([#79](https://github.com/mian196/google_photos_mobile_client/issues/79)) ([551dbcd](https://github.com/mian196/google_photos_mobile_client/commit/551dbcd9bf6d93881fca940a24a50bf245c647a9))
* add filename duplicate fallback check and failed/skipped logging ([#74](https://github.com/mian196/google_photos_mobile_client/issues/74)) ([4649cd8](https://github.com/mian196/google_photos_mobile_client/commit/4649cd87b6262f8f8569efe038669e4087f71f51))
* Add uploaded media to album ([834c2dc](https://github.com/mian196/google_photos_mobile_client/commit/834c2dc81b8de73af4d11a5764dd6a6b959d73db))
* **api_methods:** quality and device settings ([6f14c0c](https://github.com/mian196/google_photos_mobile_client/commit/6f14c0c94de047bc9d41657115e72f2ab7de9a84))
* **api_methods:** request retry mechanism ([71527c4](https://github.com/mian196/google_photos_mobile_client/commit/71527c47280a3e671872491553204110173f4d36))
* **api:** add crop parameter to get_thumbnail ([4fea3a2](https://github.com/mian196/google_photos_mobile_client/commit/4fea3a2ac4a3e8916cc28b3a4551272a5187161c))
* **api:** add get_stream_manifest for video streaming ([393de66](https://github.com/mian196/google_photos_mobile_client/commit/393de6687c70bce7e966cca7f9a56856e3c82524))
* **api:** get_stream_manifest ([3432c7f](https://github.com/mian196/google_photos_mobile_client/commit/3432c7fc29b0b1a513b7d97e86a1cd8dcf3a4d51))
* **api:** strip auth_data ([319f076](https://github.com/mian196/google_photos_mobile_client/commit/319f0765e0420dcef22dd86ea9dfcd4fe7671b0b))
* **api:** thumbnails crop arg ([a891979](https://github.com/mian196/google_photos_mobile_client/commit/a8919798868c4b4bb4d43978c1088ec666ea698c))
* **client:** args refactored, added `sha1_hash` ([479163b](https://github.com/mian196/google_photos_mobile_client/commit/479163b9bbabda76615cab01ccb28d5a119e3946))
* **client:** bearer_token property ([41af74c](https://github.com/mian196/google_photos_mobile_client/commit/41af74cdf8cc65f5cf653c3d78659b9070dc8c28))
* **client:** method `check_hash` ([492e5f5](https://github.com/mian196/google_photos_mobile_client/commit/492e5f5617601a1919ecafc844cf0087a0975fed))
* **client:** overall progress error count tracking ([cc1ba03](https://github.com/mian196/google_photos_mobile_client/commit/cc1ba0325e43fc3176cb47d3a400b116f6610ac1))
* **client:** use env varaible if not auth_data provided ([ef32f3c](https://github.com/mian196/google_photos_mobile_client/commit/ef32f3c7849747325ef48194bde4e40f4d415484))
* delete from host if uploaded ([6b1e02d](https://github.com/mian196/google_photos_mobile_client/commit/6b1e02d9d0fbbfeb6227fbe1d753aaf0006996ca))
* delete from host if uploaded ([1c733b4](https://github.com/mian196/google_photos_mobile_client/commit/1c733b4eaf6707a22bec3ac8c657447d26f7ff4c))
* display album name in the progress of adding to album ([53f07bc](https://github.com/mian196/google_photos_mobile_client/commit/53f07bc89a68185a00d57b337b7d861c5ab75ea9))
* emit machine-readable upload progress ([#75](https://github.com/mian196/google_photos_mobile_client/issues/75)) ([3ee0cc6](https://github.com/mian196/google_photos_mobile_client/commit/3ee0cc6159674d28b7c9489b06cdc53d48971a87))
* expose timeout ([46b0132](https://github.com/mian196/google_photos_mobile_client/commit/46b01320d08d7265bd7c067317532c98adbd4d1a))
* file filtering ([fa1038f](https://github.com/mian196/google_photos_mobile_client/commit/fa1038f4e9221de4149614988b363e5161595604))
* improve sync logic with cycle detection and schema migration ([8c12195](https://github.com/mian196/google_photos_mobile_client/commit/8c12195590e2d7b36bffedf6376bb59f6c6d91ae))
* improve sync logic with cycle detection and token renaming ([8a30e75](https://github.com/mian196/google_photos_mobile_client/commit/8a30e75f837f5fd6e5abc8f7ad3088098631c896))
* refactor and features ([df5d6f1](https://github.com/mian196/google_photos_mobile_client/commit/df5d6f1736a95aa3d0ed21cb324af102a4010cf4))
* support hexadecimal input hashes ([59c817e](https://github.com/mian196/google_photos_mobile_client/commit/59c817e38e26ef570f646013a72083f6ee636060))


### Bug Fixes

* [#2](https://github.com/mian196/google_photos_mobile_client/issues/2) ([1e58a4b](https://github.com/mian196/google_photos_mobile_client/commit/1e58a4ba6c8b1a7a7599d194601984fe4c301aef))
* allow hash None type in TargetMapping ([9f56d2d](https://github.com/mian196/google_photos_mobile_client/commit/9f56d2d0a51f8ad2e8e2a32c3944ea7b0ee1a201))
* allow hash None type in TargetMapping ([d2037c8](https://github.com/mian196/google_photos_mobile_client/commit/d2037c86944e775a5ab73dc10cf705311bb2d1eb))
* **api_methods:** mkv upload ([1c433bc](https://github.com/mian196/google_photos_mobile_client/commit/1c433bcf25ee3c86e5e7835a073ad95b2576434d))
* **api:** strip whitespace from auth_data ([c6c0540](https://github.com/mian196/google_photos_mobile_client/commit/c6c0540382b1d002852f48a33f8584743deaaa87))
* arg help ([b4c4396](https://github.com/mian196/google_photos_mobile_client/commit/b4c4396e7ed37c8b7466a4a4dfd44b2651bf6fa1))
* args default values ([30578ad](https://github.com/mian196/google_photos_mobile_client/commit/30578ada23cdc7bcf6ab5e82d317f81fcb118d04))
* AttributeError ([8320451](https://github.com/mian196/google_photos_mobile_client/commit/8320451a184680dd84544c84b428546b64fc679d))
* **client:** `album_limit` and `batch_size` values ([db6e7b8](https://github.com/mian196/google_photos_mobile_client/commit/db6e7b8b4e45eb349393740ae73c03a0bf287303))
* **client:** log just the path on upload error ([51ccf20](https://github.com/mian196/google_photos_mobile_client/commit/51ccf200a28dc4096188ffae0acf55c1862eb6e8))
* **client:** log just the path on upload error ([89f09ce](https://github.com/mian196/google_photos_mobile_client/commit/89f09cee23692878376b3ff0a8b1800315eb8cad))
* **client:** types ([00559d7](https://github.com/mian196/google_photos_mobile_client/commit/00559d77aca8b52b4c61fcbff7a983d41e5840ac))
* **cli:** error: --filter is required ([323ab86](https://github.com/mian196/google_photos_mobile_client/commit/323ab86024d573c1677e1862c3ee081111f8cab8))
* decode media keys as strings to avoid dict misparse ([#82](https://github.com/mian196/google_photos_mobile_client/issues/82)) ([94b1b26](https://github.com/mian196/google_photos_mobile_client/commit/94b1b267ca6819da542d4330a7dd216747eb0437)), closes [#80](https://github.com/mian196/google_photos_mobile_client/issues/80)
* delete only uploaded ([ac5a4db](https://github.com/mian196/google_photos_mobile_client/commit/ac5a4db9280bfc7677b1b240d7457da9bbf29f31))
* delete skipped files from host when delete_from_host is enabled ([a62f361](https://github.com/mian196/google_photos_mobile_client/commit/a62f3614540c340446118851fa5b3b0590dac14a))
* enable VS Code unittest discovery for *_test.py files ([274e852](https://github.com/mian196/google_photos_mobile_client/commit/274e8522aee7702efd8059b54b0eb83bf261631d))
* error text grammar ([74ff406](https://github.com/mian196/google_photos_mobile_client/commit/74ff406fd4213acc718cb104e5104edd1f35e8b4))
* increase REQUESTS_TIMEOUT ([0ef21a8](https://github.com/mian196/google_photos_mobile_client/commit/0ef21a80a1d8d354e7b167f650252d4bf5151b50))
* logic bug in _handle_target_input and typos ([555b721](https://github.com/mian196/google_photos_mobile_client/commit/555b72136ecfa1f832ca909330c7eb72e340894c))
* logic bug in _handle_target_input and typos ([21a5c90](https://github.com/mian196/google_photos_mobile_client/commit/21a5c907b420dd0e21c8df8b2c9a4aad60504355))
* minor text fixes ([f2867fe](https://github.com/mian196/google_photos_mobile_client/commit/f2867fe735f69bf4b59b339afac2aa72e2df72ea))
* rich live conflict ([35da8d9](https://github.com/mian196/google_photos_mobile_client/commit/35da8d9f41fb0de2768a9f65cbc272f64286cc59))
* rich live conflict ([100cc56](https://github.com/mian196/google_photos_mobile_client/commit/100cc568032ab1951b89fc055bf056586e1dc110))
* run migration before table creation to handle schema changes ([3366096](https://github.com/mian196/google_photos_mobile_client/commit/3366096ac5c02e5a8359ddb97b1a5b743b8e8e4c))
* use `last modified` file date as upload timestamp ([1e58a4b](https://github.com/mian196/google_photos_mobile_client/commit/1e58a4ba6c8b1a7a7599d194601984fe4c301aef))
* **utils:** requests retries ([653ee9d](https://github.com/mian196/google_photos_mobile_client/commit/653ee9dedd6a8e4703829591d4a6e6c267174d8b))


### Documentation

* clarify mobile API naming ([8105cb8](https://github.com/mian196/google_photos_mobile_client/commit/8105cb8d5193b3c4dfe41a0425fab11a1da0c1e7))

## [0.9.0](https://github.com/xob0t/gpmc/compare/v0.8.0...v0.9.0) (2026-07-16)


### Features

* add filename duplicate fallback check and failed/skipped logging ([#74](https://github.com/xob0t/gpmc/issues/74)) ([4649cd8](https://github.com/xob0t/gpmc/commit/4649cd87b6262f8f8569efe038669e4087f71f51))
* emit machine-readable upload progress ([#75](https://github.com/xob0t/gpmc/issues/75)) ([3ee0cc6](https://github.com/xob0t/gpmc/commit/3ee0cc6159674d28b7c9489b06cdc53d48971a87))


### Documentation

* clarify mobile API naming ([8105cb8](https://github.com/xob0t/gpmc/commit/8105cb8d5193b3c4dfe41a0425fab11a1da0c1e7))
