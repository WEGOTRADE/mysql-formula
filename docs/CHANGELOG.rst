
Changelog
=========

`0.56.2 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.56.1...v0.56.2>`_ (2021-09-04)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **centos7:** add correct pymysql package on cent7/saltpy3 (\ `9722b02 <https://github.com/saltstack-formulas/mysql-formula/commit/9722b0218763c56b7bb1096b421058e6898ae55e>`_\ )
* **ci:** corrected ruby last else (\ `df2fa30 <https://github.com/saltstack-formulas/mysql-formula/commit/df2fa300eff9c07e54967a3ef1366c57896b4eb5>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **centos:** add centos ci; fix test pillar (\ `060b43f <https://github.com/saltstack-formulas/mysql-formula/commit/060b43f3036bbdfd1c0910fe91ff280221ef116c>`_\ )

`0.56.1 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.56.0...v0.56.1>`_ (2021-08-25)
----------------------------------------------------------------------------------------------------------

Code Refactoring
^^^^^^^^^^^^^^^^


* **jinja:** improve indentation (\ `d09728e <https://github.com/saltstack-formulas/mysql-formula/commit/d09728e04f0405e0e085b68210210ced9d892fe4>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile+lock:** use ``ssf`` customised ``inspec`` repo [skip ci] (\ `8f91b4f <https://github.com/saltstack-formulas/mysql-formula/commit/8f91b4f3ecd2b9c9ee862aa607993f5b81ef4d6c>`_\ )
* **kitchen+ci:** update with latest ``3003.2`` pre-salted images [skip ci] (\ `d908ad5 <https://github.com/saltstack-formulas/mysql-formula/commit/d908ad5e5558e236812860095222cdfb5f80ff08>`_\ )

`0.56.0 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.55.2...v0.56.0>`_ (2021-07-19)
----------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* add Debian 11 Bullseye & update ``yamllint`` configuration [skip ci] (\ `ee34e48 <https://github.com/saltstack-formulas/mysql-formula/commit/ee34e48fae56a5ca06557d8997e47d100eef8c48>`_\ )
* **3003.1:** update inc. AlmaLinux, Rocky & ``rst-lint`` [skip ci] (\ `4d5e6d9 <https://github.com/saltstack-formulas/mysql-formula/commit/4d5e6d9e1924fdabae726b1ef6cdc58b8dcb331f>`_\ )
* **kitchen:** move ``provisioner`` block & update ``run_command`` [skip ci] (\ `f51d4ba <https://github.com/saltstack-formulas/mysql-formula/commit/f51d4ba4ced7d7a6b13da091b838e60a16be7d1b>`_\ )
* **kitchen+gitlab:** remove Ubuntu 16.04 & Fedora 32 (EOL) [skip ci] (\ `13c8450 <https://github.com/saltstack-formulas/mysql-formula/commit/13c8450069aad9bf1ff25a0c7870a82d5a0b3e7f>`_\ )
* add ``arch-master`` to matrix and update ``.travis.yml`` [skip ci] (\ `8dbff38 <https://github.com/saltstack-formulas/mysql-formula/commit/8dbff388203b9b6156d07e6cc4bb6558c7ad72e0>`_\ )

Features
^^^^^^^^


* **freebsd:** update packages from ``py37-*`` => ``py38-*`` (\ `70eeed8 <https://github.com/saltstack-formulas/mysql-formula/commit/70eeed80c1b0ce0dfd1ffe539b5e0be6ba5415fd>`_\ )
* **osfingermap:** add support for ``Debian 11`` [skip ci] (\ `3ea9b34 <https://github.com/saltstack-formulas/mysql-formula/commit/3ea9b347590e6f15761d07567a7640d138f74128>`_\ )

`0.55.2 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.55.1...v0.55.2>`_ (2021-05-07)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **salt-user:** fix setting grants for the salt user (\ `346633d <https://github.com/saltstack-formulas/mysql-formula/commit/346633d6f65a4da5e44a9e7c1cff9f00e0e2075b>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+gitlab:** adjust matrix to add ``3003`` [skip ci] (\ `3df6d64 <https://github.com/saltstack-formulas/mysql-formula/commit/3df6d6410d0ad74d51cb26032d4917617913d835>`_\ )

Documentation
^^^^^^^^^^^^^


* **readme:** fix headings [skip ci] (\ `897a83d <https://github.com/saltstack-formulas/mysql-formula/commit/897a83dc2ae0430144f5c1ef0dde29f05839fe69>`_\ )

Tests
^^^^^


* standardise use of ``share`` suite & ``_mapdata`` state [skip ci] (\ `c11750c <https://github.com/saltstack-formulas/mysql-formula/commit/c11750c9ccb702cfa28bbae4b3e2481e835729c1>`_\ )

`0.55.1 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.55.0...v0.55.1>`_ (2021-03-23)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **salt-user:** redirect error output from user access checks (\ `4cb4c05 <https://github.com/saltstack-formulas/mysql-formula/commit/4cb4c05e48272c8073b0798afa8b31f232d12674>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **commitlint:** ensure ``upstream/master`` uses main repo URL [skip ci] (\ `e20d7c6 <https://github.com/saltstack-formulas/mysql-formula/commit/e20d7c69d12777365ff95c841decfe7dc05c4227>`_\ )
* **gemfile+lock:** use ``ssf`` customised ``kitchen-docker`` repo [skip ci] (\ `63561c0 <https://github.com/saltstack-formulas/mysql-formula/commit/63561c0a2f236722b4449717e83b421a021d7093>`_\ )
* **gitlab-ci:** add ``rubocop`` linter (with ``allow_failure``\ ) [skip ci] (\ `d08b960 <https://github.com/saltstack-formulas/mysql-formula/commit/d08b960daf910f9c386523ae3d942d851cca2802>`_\ )
* **kitchen+ci:** use latest pre-salted images (after CVE) [skip ci] (\ `1af83d1 <https://github.com/saltstack-formulas/mysql-formula/commit/1af83d1fac432c9208c968182979090348dab69c>`_\ )
* **kitchen+gitlab-ci:** use latest pre-salted images [skip ci] (\ `b27382a <https://github.com/saltstack-formulas/mysql-formula/commit/b27382a76cf3f2fd40c5dc6934175186f2065720>`_\ )
* **pre-commit:** update hook for ``rubocop`` [skip ci] (\ `86397f6 <https://github.com/saltstack-formulas/mysql-formula/commit/86397f6390a6f5aab812dda258d3438674798af3>`_\ )

`0.55.0 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.54.2...v0.55.0>`_ (2020-12-16)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **percona:** fix startswith error (\ `6b39bda <https://github.com/saltstack-formulas/mysql-formula/commit/6b39bda366af83b7080e056b2f3e00408689c44b>`_\ )
* **redhat:** added missing client socket (\ `b0f370c <https://github.com/saltstack-formulas/mysql-formula/commit/b0f370cf8b60e2e8a9e281f945ae2ab435a2e63c>`_\ )
* **redhat:** update python library, add missing  deps (\ `3cab000 <https://github.com/saltstack-formulas/mysql-formula/commit/3cab000c89e5032dd7b7fc0c7cd7a68696e2445b>`_\ )
* **server:** fix ``salt-lint`` violations [skip ci] (\ `2d1c7c3 <https://github.com/saltstack-formulas/mysql-formula/commit/2d1c7c30e60b2f8a50a3964b82cb43cc5d54709b>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gitlab-ci:** use GitLab CI as Travis CI replacement (\ `fb50e26 <https://github.com/saltstack-formulas/mysql-formula/commit/fb50e26f6a2bfa38f8ed57981f4ba730cf43c34d>`_\ )
* **pre-commit:** add to formula [skip ci] (\ `11e6460 <https://github.com/saltstack-formulas/mysql-formula/commit/11e646082ec3846045edde20411615c7c0f3479b>`_\ )
* **pre-commit:** enable/disable ``rstcheck`` as relevant [skip ci] (\ `87cb5b7 <https://github.com/saltstack-formulas/mysql-formula/commit/87cb5b7c4f6096902dd97a4eeda2c238de5b0fa9>`_\ )
* **pre-commit:** finalise ``rstcheck`` configuration [skip ci] (\ `92bf43a <https://github.com/saltstack-formulas/mysql-formula/commit/92bf43a3b79fa3b1cee0f43de98dd9aac1ea2a6c>`_\ )

Features
^^^^^^^^


* **credentials:** add socket access (\ `1c70b0a <https://github.com/saltstack-formulas/mysql-formula/commit/1c70b0abc106fbce2d7f95feaf9f02dd64cddfcf>`_\ )

`0.54.2 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.54.1...v0.54.2>`_ (2020-08-27)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **indent:** properly indent file.directory block (\ `7791268 <https://github.com/saltstack-formulas/mysql-formula/commit/7791268d133d557d21414365db59dc14c8f97f74>`_\ ), closes `#250 <https://github.com/saltstack-formulas/mysql-formula/issues/250>`_

`0.54.1 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.54.0...v0.54.1>`_ (2020-08-24)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **freebsd:** upgrade to mysql57-server (\ `ec68199 <https://github.com/saltstack-formulas/mysql-formula/commit/ec681995b4f7e23a8dbec63809d3704f19ec9299>`_\ )

`0.54.0 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.53.0...v0.54.0>`_ (2020-07-10)
----------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** use ``saltimages`` Docker Hub where available [skip ci] (\ `b37a8a7 <https://github.com/saltstack-formulas/mysql-formula/commit/b37a8a7c970cb30ed18f04c4103c5f553557699d>`_\ )

Features
^^^^^^^^


* **socket_authentication:** allow unix_socket authentication (\ `8eccd5a <https://github.com/saltstack-formulas/mysql-formula/commit/8eccd5a68cadde02f54467a7fb9e370d2ee7d574>`_\ )

`0.53.0 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.52.7...v0.53.0>`_ (2020-06-01)
----------------------------------------------------------------------------------------------------------

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen+travis:** use latest pre-salted images (\ `7ea518a <https://github.com/saltstack-formulas/mysql-formula/commit/7ea518a3919f1a59bc6ae821bc0df7577629059a>`_\ )
* **travis:** add notifications => zulip [skip ci] (\ `8adfc4b <https://github.com/saltstack-formulas/mysql-formula/commit/8adfc4bb4fbb49548cf46d277a0403b89c180b1a>`_\ )

Features
^^^^^^^^


* **focal:** add settings for ``ubuntu-20.04`` (\ `0d77164 <https://github.com/saltstack-formulas/mysql-formula/commit/0d77164f394909ec371f39cb41a4920c82e75052>`_\ )

`0.52.7 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.52.6...v0.52.7>`_ (2020-05-19)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **osfamilymap.yaml:** update SUSE defaults (\ `8ee79a7 <https://github.com/saltstack-formulas/mysql-formula/commit/8ee79a7bb03488e4c3632a1dcfe143696a11aad5>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile.lock:** add to repo with updated ``Gemfile`` [skip ci] (\ `9e9fa3e <https://github.com/saltstack-formulas/mysql-formula/commit/9e9fa3e3d15e25ad22f75eae61af4883c79b7c0f>`_\ )
* **kitchen+travis:** remove ``master-py2-arch-base-latest`` [skip ci] (\ `c1dddc3 <https://github.com/saltstack-formulas/mysql-formula/commit/c1dddc3a8d561847094bbe23fe2c764c8fdf79de>`_\ )
* **workflows/commitlint:** add to repo [skip ci] (\ `b4c6570 <https://github.com/saltstack-formulas/mysql-formula/commit/b4c65702b91e8813741bf72008e41d1d8dfc735d>`_\ )

`0.52.6 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.52.5...v0.52.6>`_ (2020-04-17)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **reload-modules:** do ``reload_modules`` on py module installation (\ `2b6e704 <https://github.com/saltstack-formulas/mysql-formula/commit/2b6e704c96d0373aadb56f90d758c960f538abdb>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **gemfile:** restrict ``train`` gem version until upstream fix [skip ci] (\ `04f75a7 <https://github.com/saltstack-formulas/mysql-formula/commit/04f75a7a3b43de9425a8f36dc202b7ecf0c4f856>`_\ )
* **kitchen:** avoid using bootstrap for ``master`` instances [skip ci] (\ `ef7a2ce <https://github.com/saltstack-formulas/mysql-formula/commit/ef7a2ce2d857dd271ec0704ab951c8337cb6b64e>`_\ )
* **travis:** use ``major.minor`` for ``semantic-release`` version [skip ci] (\ `b4f5f79 <https://github.com/saltstack-formulas/mysql-formula/commit/b4f5f79781631d7d31061b880df3066ac5bc5860>`_\ )

`0.52.5 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.52.4...v0.52.5>`_ (2019-12-10)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **db_load:** preserve space between -h and -p on the db load ``cmd.wait`` (\ `a05f263 <https://github.com/saltstack-formulas/mysql-formula/commit/a05f263f4b9eac52a5854fd57a6a24f997ccb291>`_\ )

`0.52.4 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.52.3...v0.52.4>`_ (2019-12-03)
----------------------------------------------------------------------------------------------------------

Styles
^^^^^^


* remove previous line from jinja directives (\ `ec0e2a7 <https://github.com/saltstack-formulas/mysql-formula/commit/ec0e2a765a587d0df94b0afb9f7a4ef78a5319ab>`_\ )

`0.52.3 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.52.2...v0.52.3>`_ (2019-12-03)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **mac_shortcut.sh:** fix ``shellcheck`` errors (\ `7b309f8 <https://github.com/saltstack-formulas/mysql-formula/commit/7b309f8da272ebdcb36dbfa7619a0fc9872a79a7>`_\ )
* **release.config.js:** use full commit hash in commit link [skip ci] (\ `3f51b8b <https://github.com/saltstack-formulas/mysql-formula/commit/3f51b8bbc231a7455e6763b415221abff636d8a2>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** use ``debian-10-master-py3`` instead of ``develop`` [skip ci] (\ `5efe938 <https://github.com/saltstack-formulas/mysql-formula/commit/5efe9387fde63e0c09d99d5771f3b623fb934242>`_\ )
* **kitchen:** use ``develop`` image until ``master`` is ready (\ ``amazonlinux``\ ) [skip ci] (\ `63bfb4a <https://github.com/saltstack-formulas/mysql-formula/commit/63bfb4a0f25b62bdc45c1738d438ce5ec64f2183>`_\ )
* **kitchen+travis:** upgrade matrix after ``2019.2.2`` release [skip ci] (\ `27ac5a3 <https://github.com/saltstack-formulas/mysql-formula/commit/27ac5a3f684325a8e15736bb85d4774807061534>`_\ )
* **travis:** apply changes from build config validation [skip ci] (\ `d520848 <https://github.com/saltstack-formulas/mysql-formula/commit/d520848c815a9c2815ee3f1943e3e3962a26c7cf>`_\ )
* **travis:** opt-in to ``dpl v2`` to complete build config validation [skip ci] (\ `1a8d914 <https://github.com/saltstack-formulas/mysql-formula/commit/1a8d914fbd5e43f78ee2334b9c5ccd51ee65ad57>`_\ )
* **travis:** quote pathspecs used with ``git ls-files`` [skip ci] (\ `3fb5a82 <https://github.com/saltstack-formulas/mysql-formula/commit/3fb5a82de66dda9a05decc5ee7263729ef913533>`_\ )
* **travis:** run ``shellcheck`` during lint job [skip ci] (\ `0931835 <https://github.com/saltstack-formulas/mysql-formula/commit/0931835f1cfc77022a43242bd3ab04cbed2a3a02>`_\ )
* **travis:** update ``salt-lint`` config for ``v0.0.10`` [skip ci] (\ `1512279 <https://github.com/saltstack-formulas/mysql-formula/commit/1512279c2eac26638720461cc7e847d93d2c77d6>`_\ )
* **travis:** use build config validation (beta) [skip ci] (\ `40d4b97 <https://github.com/saltstack-formulas/mysql-formula/commit/40d4b9763f252f5811d31b2b2df156260bde2b6d>`_\ )

Documentation
^^^^^^^^^^^^^


* **contributing:** remove to use org-level file instead [skip ci] (\ `6afcc80 <https://github.com/saltstack-formulas/mysql-formula/commit/6afcc80396dc4ec2044d8611f18a6ed9075c6a52>`_\ )
* **readme:** update link to ``CONTRIBUTING`` [skip ci] (\ `01f25a3 <https://github.com/saltstack-formulas/mysql-formula/commit/01f25a3ebfbf59d1db2bec73bc5fef9d8bcafd7e>`_\ )

Performance Improvements
^^^^^^^^^^^^^^^^^^^^^^^^


* **travis:** improve ``salt-lint`` invocation [skip ci] (\ `1980c63 <https://github.com/saltstack-formulas/mysql-formula/commit/1980c634b9021c7d29be914bd2a63ddf3c31c8ad>`_\ )

`0.52.2 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.52.1...v0.52.2>`_ (2019-10-11)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **rubocop:** add fixes using ``rubocop --safe-auto-correct`` (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/fca3b04>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/b2b8863>`_\ )
* **travis:** merge ``rubocop`` linter into main ``lint`` job (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/26dc562>`_\ )

`0.52.1 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.52.0...v0.52.1>`_ (2019-10-10)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **server.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/764dd0c>`_\ )
* **user.sls:** fix ``salt-lint`` errors (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/a014e55>`_\ )

Continuous Integration
^^^^^^^^^^^^^^^^^^^^^^


* **kitchen:** change ``log_level`` to ``debug`` instead of ``info`` (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/75fd8dc>`_\ )
* **kitchen:** install required packages to bootstrapped ``opensuse`` [skip ci] (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/8b89ebc>`_\ )
* **kitchen:** use bootstrapped ``opensuse`` images until ``2019.2.2`` [skip ci] (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/4bdaab7>`_\ )
* **platform:** add ``arch-base-latest`` (commented out for now) [skip ci] (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/5c20c9b>`_\ )
* **yamllint:** add rule ``empty-values`` & use new ``yaml-files`` setting (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/2322ff6>`_\ )
* merge travis matrix, add ``salt-lint`` & ``rubocop`` to ``lint`` job (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/00494d5>`_\ )
* use ``dist: bionic`` & apply ``opensuse-leap-15`` SCP error workaround (\ ` <https://github.com/saltstack-formulas/mysql-formula/commit/05b1cef>`_\ )

`0.52.0 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.51.0...v0.52.0>`_ (2019-08-17)
----------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **yamllint:** include for this repo and apply rules throughout (\ `9f739fa <https://github.com/saltstack-formulas/mysql-formula/commit/9f739fa>`_\ )

`0.51.0 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.50.0...v0.51.0>`_ (2019-08-08)
----------------------------------------------------------------------------------------------------------

Bug Fixes
^^^^^^^^^


* **connector:** fix typos (connnector) and missing ``enabled`` (\ `bdee94a <https://github.com/saltstack-formulas/mysql-formula/commit/bdee94a>`_\ )

Features
^^^^^^^^


* **linux:** archlinux support (no osmajorrelase grain) (\ `4b4ad88 <https://github.com/saltstack-formulas/mysql-formula/commit/4b4ad88>`_\ )

`0.50.0 <https://github.com/saltstack-formulas/mysql-formula/compare/v0.49.0...v0.50.0>`_ (2019-07-12)
----------------------------------------------------------------------------------------------------------

Features
^^^^^^^^


* **semantic-release:** implement for this formula (\ `1d2e2f5 <https://github.com/saltstack-formulas/mysql-formula/commit/1d2e2f5>`_\ )
