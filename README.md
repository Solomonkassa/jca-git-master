```
jca-git-master-production/
├── DEBIAN/
│   ├── control
│   ├── preinst
│   ├── postinst
│   ├── prerm
│   ├── postrm
│   ├── conffiles
│   └── templates
├── etc/
│   ├── apt/
│   │   └── sources.list.d/
│   │       └── jedancodeacademy.list
│   ├── jca-git-master/
│   │   ├── config.yaml
│   │   ├── profiles/
│   │   │   ├── beginner.yaml
│   │   │   ├── intermediate.yaml
│   │   │   ├── advanced.yaml
│   │   │   └── enterprise.yaml
│   │   └── exercises/
│   │       ├── git-basics.yaml
│   │       ├── branching.yaml
│   │       ├── github.yaml
│   │       └── advanced.yaml
│   └── profile.d/
│       └── jca-git-master.sh
├── usr/
│   ├── bin/
│   │   └── jca-git-master
│   ├── sbin/
│   │   └── jca-git-master-setup
│   ├── share/
│   │   ├── jca-git-master/
│   │   │   ├── bin/
│   │   │   │   ├── jca-git-master
│   │   │   │   ├── jca-git-master-completion
│   │   │   │   └── jca-git-master-utils
│   │   │   ├── lib/
│   │   │   │   ├── modules/
│   │   │   │   │   ├── install.sh
│   │   │   │   │   ├── config.sh
│   │   │   │   │   ├── learning.sh
│   │   │   │   │   ├── github.sh
│   │   │   │   │   └── exercises.sh
│   │   │   │   ├── utils/
│   │   │   │   │   ├── colors.sh
│   │   │   │   │   ├── logging.sh
│   │   │   │   │   ├── validators.sh
│   │   │   │   │   ├── animations.sh
│   │   │   │   │   └── progress.sh
│   │   │   │   └── core/
│   │   │   │       ├── engine.sh
│   │   │   │       ├── config-manager.sh
│   │   │   │       └── analytics.sh
│   │   │   ├── data/
│   │   │   │   ├── exercises/
│   │   │   │   │   ├── 01-git-basics/
│   │   │   │   │   ├── 02-branching/
│   │   │   │   │   ├── 03-github/
│   │   │   │   │   └── 04-advanced/
│   │   │   │   ├── cheat-sheets/
│   │   │   │   │   ├── git-cheat-sheet.md
│   │   │   │   │   ├── github-cheat-sheet.md
│   │   │   │   │   └── advanced-cheat-sheet.md
│   │   │   │   ├── templates/
│   │   │   │   │   ├── project-templates/
│   │   │   │   │   │   ├── simple-web/
│   │   │   │   │   │   ├── node-api/
│   │   │   │   │   │   └── python-cli/
│   │   │   │   │   └── config-templates/
│   │   │   │   └── i18n/
│   │   │   │       ├── en_US/
│   │   │   │       ├── es_ES/
│   │   │   │       └── fr_FR/
│   │   │   ├── themes/
│   │   │   │   ├── default/
│   │   │   │   ├── dark/
│   │   │   │   └── light/
│   │   │   └── docs/
│   │   │       ├── man/
│   │   │       │   └── man1/
│   │   │       │       └── jca-git-master.1
│   │   │       ├── html/
│   │   │       └── examples/
│   │   ├── man/
│   │   │   └── man1/
│   │   │       └── jca-git-master.1.gz
│   │   ├── bash-completion/
│   │   │   └── completions/
│   │   │       └── jca-git-master
│   │   ├── zsh/
│   │   │   └── site-functions/
│   │   │       └── _jca-git-master
│   │   ├── fish/
│   │   │   └── completions/
│   │   │       └── jca-git-master.fish
│   │   ├── applications/
│   │   │   └── jca-git-master.desktop
│   │   ├── icons/
│   │   │   └── hicolor/
│   │   │       ├── 48x48/
│   │   │       │   └── apps/
│   │   │       │       └── jca-git-master.png
│   │   │       └── scalable/
│   │   │           └── apps/
│   │   │               └── jca-git-master.svg
│   │   └── doc/
│   │       └── jca-git-master/
│   │           ├── changelog.Debian.gz
│   │           ├── copyright
│   │           └── README.Debian
│   └── lib/
│       └── systemd/
│           └── system/
│               └── jca-git-master-update.service
├── var/
│   ├── lib/
│   │   └── jca-git-master/
│   │       ├── cache/
│   │       ├── logs/
│   │       └── state/
│   ├── log/
│   │   └── jca-git-master/
│   └── tmp/
│       └── jca-git-master/
├── opt/
│   └── jca-git-master/
│       └── examples/
│           ├── sample-projects/
│           └── workflows/
├── home/
│   └── .local/
│       └── share/
│           └── jca-git-master/
│               ├── user-profiles/
│               ├── progress-data/
│               └── certificates/
├── build/
│   ├── debian/
│   │   ├── rules
│   │   ├── compat
│   │   ├── changelog
│   │   └── copyright
│   └── packagecloud/
│       ├── publish.sh
│       └── config.yaml
├── scripts/
│   ├── build-deb.sh
│   ├── build-rpm.sh
│   ├── package.sh
│   ├── publish.sh
│   └── test-install.sh
├── tests/
│   ├── integration/
│   ├── unit/
│   └── functional/
├── src/
│   ├── main.sh
│   ├── modules/
│   └── utils/
├── config/
│   ├── packagecloud.yaml
│   ├── apt-repo.yaml
│   └── signing.yaml
├── docs/
│   ├── APT_INSTALLATION.md
│   ├── BUILDING.md
│   ├── SIGNING.md
│   └── PUBLISHING.md
├── .github/
│   └── workflows/
│       ├── build-deb.yml
│       ├── publish-apt.yml
│       └── release.yml
├── Makefile
├── pyproject.toml
├── setup.py
├── requirements.txt
├── LICENSE
├── README.md
└── CHANGELOG.md
```
* Solomon Kassa *
