# Changelog

### [0.9.6](https://www.github.com/werf/kubedog/compare/v0.9.5...v0.9.6) (2022-07-29)


### Bug Fixes

* **generic:** ignore jsonpath errs on Condition search ([8d88c65](https://www.github.com/werf/kubedog/commit/8d88c6509e3ac1c12a8a564aebb9e04d2b7c73e0))

### [0.9.5](https://www.github.com/werf/kubedog/compare/v0.9.4...v0.9.5) (2022-07-26)


### Bug Fixes

* **generic:** add logging and don't retry fatal errors on List/Watch ([246d454](https://www.github.com/werf/kubedog/commit/246d45452ae7686584d67dfa4763bf6563907a30))
* **generic:** Condition output was malformed ([8c05e40](https://www.github.com/werf/kubedog/commit/8c05e40d9a5381c88b38982d284e6d4f8653d917))
* hide Header if no resources of such type being tracked ([232c4ed](https://www.github.com/werf/kubedog/commit/232c4ede20fa52f18a2e574c173b94e6d0a114cd))

### [0.9.4](https://www.github.com/werf/kubedog/compare/v0.9.3...v0.9.4) (2022-07-21)


### Bug Fixes

* **generic-tracker:** improve logging + few possible fixes ([3524520](https://www.github.com/werf/kubedog/commit/352452071afd55b57ef721b8b271e9acc9849c75))

### [0.9.3](https://www.github.com/werf/kubedog/compare/v0.9.2...v0.9.3) (2022-07-20)


### Bug Fixes

* Generic tracker hangs if no list/watch access ([946d650](https://www.github.com/werf/kubedog/commit/946d650746a249a92c0cdbc241958ecb519c8a88))

### [0.9.2](https://www.github.com/werf/kubedog/compare/v0.9.1...v0.9.2) (2022-07-19)


### Bug Fixes

* improve generic tracker output ([60602b0](https://www.github.com/werf/kubedog/commit/60602b05cc942cd27ef5354be15c2d744a2e5092))

### [0.9.1](https://www.github.com/werf/kubedog/compare/v0.9.0...v0.9.1) (2022-07-18)


### Bug Fixes

* increase noActivityTimeout from 1.5 to 4min ([00b49d8](https://www.github.com/werf/kubedog/commit/00b49d814dc0d807e374967fc19ce9d38c9dde28))
* reword no activity error message ([e4b1302](https://www.github.com/werf/kubedog/commit/e4b13020cca2f0a175c51316945dd478b79d4d9a))

## [0.9.0](https://www.github.com/werf/kubedog/compare/v0.8.0...v0.9.0) (2022-07-18)


### Features

* improved Generic progress status ([5f68bca](https://www.github.com/werf/kubedog/commit/5f68bca131024ed5a5b791f3194f98e3304e5b16))


### Bug Fixes

* job duration stops changing ([4aa62c3](https://www.github.com/werf/kubedog/commit/4aa62c3bc21778b4fd2aff2c7b28432d54a3524c))

## [0.8.0](https://www.github.com/werf/kubedog/compare/v0.7.1...v0.8.0) (2022-07-15)


### Features

* show Ready resources only once ([322a781](https://www.github.com/werf/kubedog/commit/322a781e52bb75be2ab39c2bc22ff1ab091c39dd))

### [0.7.1](https://www.github.com/werf/kubedog/compare/v0.7.0...v0.7.1) (2022-07-06)


### Bug Fixes

* non-blocking mode doesn't work ([71e8826](https://www.github.com/werf/kubedog/commit/71e88261b930965dd473af7274b0ec3f9dd7e9ba))

## [0.7.0](https://www.github.com/werf/kubedog/compare/v0.6.4...v0.7.0) (2022-07-05)


### Features

* generic resources tracking ([ba88553](https://www.github.com/werf/kubedog/commit/ba88553162024253f8d00be930931ebca0975b07))


### Bug Fixes

* **kube:** do not use memcache discovery client for base64 kubeconfig ([d1cd71b](https://www.github.com/werf/kubedog/commit/d1cd71bd4f07f0913acb7c2bfdee72ba865cf9a0))
* **kube:** fix GetAllContextsClients not working in in-cluster mode ([802c1b0](https://www.github.com/werf/kubedog/commit/802c1b0fd9afde8ca41eeee7719f0ddb0a4f9dfd))

### [0.6.4](https://www.github.com/werf/kubedog/compare/v0.6.3...v0.6.4) (2022-02-22)


### Bug Fixes

* **kube-client:** support kube config merge list option for KubeClientGetter ([ae4dd95](https://www.github.com/werf/kubedog/commit/ae4dd95bf6e7df5ca850a81dd6078dc801217242))

### [0.6.3](https://www.github.com/werf/kubedog/compare/v0.6.2...v0.6.3) (2022-02-07)


### Bug Fixes

* **elimination:** fixed possible race-condition which could result in haning elimination tracker ([8007d2e](https://www.github.com/werf/kubedog/commit/8007d2ebfcda7ace85fa43f77b24e0d2b63114ac))
* **elimination:** refactor elimination tracker, fix "panic: close of closed channel" ([8a2f13e](https://www.github.com/werf/kubedog/commit/8a2f13ef93de699ce1225d6aa2824e4b91ec19db))
* **kube:** fix kube client ignores KUBECONFIG ([f7d600a](https://www.github.com/werf/kubedog/commit/f7d600a51cbcb3fdf9df8f11028b4888ac4d61fe))
* trigger release ([6163bc9](https://www.github.com/werf/kubedog/commit/6163bc9d2a5f09e1353a1c88cc869c1a7d41392c))

### [0.6.2](https://www.github.com/werf/kubedog/compare/v0.6.1...v0.6.2) (2021-09-16)


### Bug Fixes

* correction release ([da7c662](https://www.github.com/werf/kubedog/commit/da7c6620158ebbb5e0bd3b7026173517ec38900c))

### [0.6.1](https://www.github.com/werf/kubedog/compare/v0.6.0...v0.6.1) (2021-09-09)


### Bug Fixes

* **kube-client:** support KUBECONFIG-like list of config paths ([4433815](https://www.github.com/werf/kubedog/commit/44338155c27b2c25963aea72123f3dea2045c572))
