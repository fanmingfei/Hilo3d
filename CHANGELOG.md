## [1.15.19](https://github.com/hiloteam/Hilo3d/compare/1.15.18...1.15.19) (2021-05-20)


### Features

* add wrapS & wrapT property of the framebuffer ([eaae512](https://github.com/hiloteam/Hilo3d/commit/eaae5129fc4324ece40d652bf7b76c625ef36d9b))



## [1.15.18](https://github.com/hiloteam/Hilo3d/compare/1.15.17...1.15.18) (2021-05-14)
* update doc & .d.ts 


## [1.15.17](https://github.com/hiloteam/Hilo3d/compare/1.15.16...1.15.17) (2021-02-22)


### Bug Fixes

* glTF texture should ignore texture colorspace conversion, fix [#32](https://github.com/hiloteam/Hilo3d/issues/32) ([08f1252](https://github.com/hiloteam/Hilo3d/commit/08f1252e4658131f425419f25c21313859645aea))


### Features

* add colorSpaceConversion property of the texture ([ddd170b](https://github.com/hiloteam/Hilo3d/commit/ddd170be451b7f76103f54d31ab934398254da2b))
* add PBRMaterial emissionFactor support ([de7cf25](https://github.com/hiloteam/Hilo3d/commit/de7cf25fd36cbc845fa829f7270f95e8f7aaa795))



## [1.15.16](https://github.com/hiloteam/Hilo3d/compare/1.15.15...1.15.16) (2021-01-20)

* update doc & .d.ts 
* refactor: optimize multiple destroy framebuffer ([c68599e](https://github.com/hiloteam/Hilo3d/commit/c68599e131c2f1b258d5675884cdcc06fcdda279))

## [1.15.15](https://github.com/hiloteam/Hilo3d/compare/1.15.14...1.15.15) (2021-01-05)


### Bug Fixes

* Animation.clipTime should be updated while updating the animStatesList ([447ae1e](https://github.com/hiloteam/Hilo3d/commit/447ae1e75a2213865a9ed42ac08a048ecf0ac9a5))



## [1.15.14](https://github.com/hiloteam/Hilo3d/compare/1.15.13...1.15.14) (2020-12-15)


### Features

* add LoadCache.getLoaded ([302c690](https://github.com/hiloteam/Hilo3d/commit/302c690b341c30537510f8b1b56cccc491a217b8))
* add Loader.preHandlerUrl ([ed7ff87](https://github.com/hiloteam/Hilo3d/commit/ed7ff8715701bbd5d81278985d88b76597297171))



## [1.15.13](https://github.com/hiloteam/Hilo3d/compare/1.15.12...1.15.13) (2020-11-18)


### Bug Fixes

* RenderList.useInstanced should update after renderer init ([d91293e](https://github.com/hiloteam/Hilo3d/commit/d91293ec2cefb7041ceb727aa07db7b37f229ba4))



## [1.15.12](https://github.com/hiloteam/Hilo3d/compare/1.15.11...1.15.12) (2020-11-05)


### Bug Fixes

* Semantic Tangent data should also be returned when there is no normal map ([c7b261b](https://github.com/hiloteam/Hilo3d/commit/c7b261b08803b6c4a0b185a9bac26e8725cf3e5d))


### Features

* Add GLTFLoader KHR_materials_clearcoat extension support ([0cfa90c](https://github.com/hiloteam/Hilo3d/commit/0cfa90c5109f8cd06aaa0478cc93fae1e4aeed00))
* Add material stencil support, close [#30](https://github.com/hiloteam/Hilo3d/issues/30) ([6dbb2c1](https://github.com/hiloteam/Hilo3d/commit/6dbb2c1530e47ba8a5ab5e148cdc4565a921cded))
* Add PBRMaterial Clearcoat support, close [#15](https://github.com/hiloteam/Hilo3d/issues/15) ([b83cbe6](https://github.com/hiloteam/Hilo3d/commit/b83cbe62dd243e1987573ab85871c5f64aaef68e))



## [1.15.11](https://github.com/hiloteam/Hilo3d/compare/1.15.10...1.15.11) (2020-10-19)


### Bug Fixes

* attribute pointer should use GeometryData.size ([bdab767](https://github.com/hiloteam/Hilo3d/commit/bdab767f621b17cb5fdd00ce633c1571383f91b0))



## [1.15.10](https://github.com/hiloteam/Hilo3d/compare/1.15.9...1.15.10) (2020-10-13)


### Bug Fixes

* Add light.isDirty and fix the bug that directionalLight lignt shadow does not update ([d808a89](https://github.com/hiloteam/Hilo3d/commit/d808a8992366c9d7537a26836f472bfd4ae1d051))


### Features

* add material.frontFace ([ef85b56](https://github.com/hiloteam/Hilo3d/commit/ef85b56f2eb1170ac2763deee2d059d514c08297))



## [1.15.9](https://github.com/hiloteam/Hilo3d/compare/1.15.8...1.15.9) (2020-09-10)


### Bug Fixes

* capabilities remove duplicate MAX_COMBINED_TEXTURE_IMAGE_UNITS ([f601071](https://github.com/hiloteam/Hilo3d/commit/f6010717e78dcf3e96e482797016bf71143e8d32))


### Features

* add userData property to Node,Geometry,Material and Skeleton ([40db285](https://github.com/hiloteam/Hilo3d/commit/40db285bfd5e3299b8e94931bed453b2a583d964))



## [1.15.8](https://github.com/hiloteam/Hilo3d/compare/1.15.7...1.15.8) (2020-09-01)
* update doc & .d.ts 



## [1.15.7](https://github.com/hiloteam/Hilo3d/compare/1.15.6...1.15.7) (2020-08-31)


### Bug Fixes

* iOS 9 doesn't support TypedArray slice, add polyfill ([7ad428a](https://github.com/hiloteam/Hilo3d/commit/7ad428ac71cd8a72ed8f601dd8e43097de7075ee))



## [1.15.6](https://github.com/hiloteam/Hilo3d/compare/1.15.5...1.15.6) (2020-08-26)
* update doc & .d.ts 


## [1.15.5](https://github.com/hiloteam/Hilo3d/compare/1.15.4...1.15.5) (2020-07-31)


### Bug Fixes

* vao.getResources miss checking whether the attribute is empty ([40ea681](https://github.com/hiloteam/Hilo3d/commit/40ea681bc8189081a784600522977d17e48a8486))


### Features

* add pbrMaterial.isSpecularEnvMapIncludeMipmaps ([#23](https://github.com/hiloteam/Hilo3d/issues/23)) ([fea3cdf](https://github.com/hiloteam/Hilo3d/commit/fea3cdfaded3c34452ba7bcf2273e74fd5fa76cb))



## [1.15.4](https://github.com/hiloteam/Hilo3d/compare/1.15.3...1.15.4) (2020-07-07)


### Bug Fixes

* skeleton.clone should also clone jointNames ([8168c64](https://github.com/hiloteam/Hilo3d/commit/8168c6457fb51f5d5df1119dde202956b0a5ac8e))



## [1.15.3](https://github.com/hiloteam/Hilo3d/compare/1.15.2...1.15.3) (2020-07-03)


### Bug Fixes

* skinnedMesh bone position is wrong under special circumstances ([cccd91e](https://github.com/hiloteam/Hilo3d/commit/cccd91e0dc2c552922c0083293532530ee56428d))



## [1.15.2](https://github.com/hiloteam/Hilo3d/compare/1.15.1...1.15.2) (2020-06-30)


### Bug Fixes

* ResourceManager.destroyUnsuedResource parameter become optional ([3e15fbe](https://github.com/hiloteam/Hilo3d/commit/3e15fbe9d6c141e580e85bfe97bd11cb253c4d0d))



## [1.15.1](https://github.com/hiloteam/Hilo3d/compare/1.15.0...1.15.1) (2020-06-24)


### Features

* add skeleton.resetJointNamesByNodeName ([91418e4](https://github.com/hiloteam/Hilo3d/commit/91418e4e3521a33e9b3dcf5a05df0da7f4460dee))



# [1.15.0](https://github.com/hiloteam/Hilo3d/compare/1.14.0...1.15.0) (2020-06-24)


### Bug Fixes

* cubic spline interpolation for quaternions is wrong ([47a93ab](https://github.com/hiloteam/Hilo3d/commit/47a93abef05435236dab150146e37031476c113c))
* geometryData bindLayout change should repoint attribute ([25d1282](https://github.com/hiloteam/Hilo3d/commit/25d12826b77dbfdff51ff647aaca90dcbea0be93))


### Features

* Add easier log level control ([b0a2870](https://github.com/hiloteam/Hilo3d/commit/b0a28708be3fbfa5714c4daeee6bbd1965d4a094))
* add Skeleton ([#9](https://github.com/hiloteam/Hilo3d/issues/9)) ([7944d70](https://github.com/hiloteam/Hilo3d/commit/7944d70eed88a694875e4a8842c53131a490f982))
* add SkinedMesh.resetJointNamesByNodeName ([14f095b](https://github.com/hiloteam/Hilo3d/commit/14f095b49de7a8819563b2ddc331069019e0bbeb))
* add skinedMesh.resetSkinIndices ([b7df689](https://github.com/hiloteam/Hilo3d/commit/b7df689785484f731fb1952ad9783926850d8ee8))


### Performance Improvements

* improve resource management performance ([#10](https://github.com/hiloteam/Hilo3d/issues/10)) ([6ff8cbd](https://github.com/hiloteam/Hilo3d/commit/6ff8cbd73f622ac2d47a895e797dabfca37084aa))



# [1.14.0](https://github.com/hiloteam/Hilo3d/compare/1.13.47...1.14.0) (2020-05-06)


### Bug Fixes

* GLTFParser.getImageType use indexOf check support type ([262dfb8](https://github.com/hiloteam/Hilo3d/commit/262dfb8d931b421a0d56b2bb7ef1522e6c6f8682))


### Features

* add GeometryData.getCopy ([4a03269](https://github.com/hiloteam/Hilo3d/commit/4a0326911c0cd83dcb362ef5c2d19a0c9614ab36))
* AnimationStates support custom State handler register ([cda1d01](https://github.com/hiloteam/Hilo3d/commit/cda1d012e0596c7114a0f8eac9ab3e83f7ad1141))



## [1.13.47](https://github.com/hiloteam/Hilo3d/compare/1.13.46...1.13.47) (2020-01-07)


### Bug Fixes

* LazyTexture release ktx image buffer data has not work ([321f017](https://github.com/hiloteam/Hilo3d/commit/321f017c20f6ef49b91704def1901831626f3b4a))



## [1.13.46](https://github.com/hiloteam/Hilo3d/compare/1.13.45...1.13.46) (2019-12-31)


### Performance Improvements

* optimize Buffer.uploadGeometryData ([152ec21](https://github.com/hiloteam/Hilo3d/commit/152ec2156002b02ca11a3a4dd8d23ce735176d44))


