## [0.1.2](https://github.com/gliech/reflector-ansible-role/compare/v0.1.1...v0.1.2) (2021-08-21)


### Bug Fixes

* **LICENSE:** clarify how to refer to the copyright owner in clause 3 ([b7dce3b](https://github.com/gliech/reflector-ansible-role/commit/b7dce3bbada23178c9b7b1dbea899f3dcba44f84))


### Tests

* **molecule:** use container at master branch tag ([a549334](https://github.com/gliech/reflector-ansible-role/commit/a5493345b51038ffd37d7f6d39aa7621ee6c5f68))
* add option to switch molecule driver ([81c9f2e](https://github.com/gliech/reflector-ansible-role/commit/81c9f2e19804d16167487fb3f33804f54442d83c))
* verify state after converge ([ea7a747](https://github.com/gliech/reflector-ansible-role/commit/ea7a7474294d30a88078acbcb9acc2838d4c8f5f))


### Continuous Integration

* **fix:** pdm install mode ([e146053](https://github.com/gliech/reflector-ansible-role/commit/e14605324393e20451b93d9d63e1c5f0c6145579))
* **fix:** pdm run instead of direct invocation of molecule ([6fa6d6a](https://github.com/gliech/reflector-ansible-role/commit/6fa6d6aac468bdeac574e92a120eab0797c4424a))
* change workflow triggers ([65e7345](https://github.com/gliech/reflector-ansible-role/commit/65e734551b8d47b44aec955717506207dacc43a9))
* force colorized output ([738df6a](https://github.com/gliech/reflector-ansible-role/commit/738df6a07d0d4c2b70598cc7f684f562f08479d6))
* new python package manager ([d62bec6](https://github.com/gliech/reflector-ansible-role/commit/d62bec62a7c4e34434e519af0b202ca87becef1c))
* **fix:** single quotes in gh-actions expression ([bad9026](https://github.com/gliech/reflector-ansible-role/commit/bad902629b0f3d17e13f227436ac48c6bb3f1850))
* fix cache key ([4a0509e](https://github.com/gliech/reflector-ansible-role/commit/4a0509edd61a7b414f3c436dc06395375744cf28))
* override default molecule driver ([c6a46dc](https://github.com/gliech/reflector-ansible-role/commit/c6a46dcd489ef60a24e103a64cb0ad7d0c3bab36))

## [0.1.1](https://github.com/gliech/reflector-ansible-role/compare/v0.1.0...v0.1.1) (2020-09-13)


### Bug Fixes

* explicit file permissions ([c82067c](https://github.com/gliech/reflector-ansible-role/commit/c82067c076f9c091abf9ef6bf72fcac390a6dd88))


### Tests

* add molecule environment ([8174125](https://github.com/gliech/reflector-ansible-role/commit/8174125e5efd919e19781f31409822a3997a069d))
* try docker backend ([53343ee](https://github.com/gliech/reflector-ansible-role/commit/53343ee8c2d8d7619b2c1e37bf51c0a85666b44c))


### Continuous Integration

* add cache step ([e8f28f5](https://github.com/gliech/reflector-ansible-role/commit/e8f28f51219b168c227b07ecfd1328e0270e488e))
* change working directory for run tasks ([ea099ed](https://github.com/gliech/reflector-ansible-role/commit/ea099ed67d81a7aa2975dbad22150ff39275383d))
* correct checkout repository name ([c840c95](https://github.com/gliech/reflector-ansible-role/commit/c840c95aa27c827490f480579f87c4a3b348cd5c))
* github actions pipeline with semrel ([486ae2e](https://github.com/gliech/reflector-ansible-role/commit/486ae2edb55c64c225d8dc8aea121864dd5402ef))