### Project Information

* <i class="fas fa-code" style="color:#233e81;"></i> Code
* <i class="fas fa-toolbox" style="color:#233e81;"></i> Builder
* <i class="fas fa-user-secret" style="color:#233e81;"></i> Breaker

### Downloads or Social Links
* [Releases](https://github.com/owasp-noir/noir/releases)
* [Homebrew](https://formulae.brew.sh/formula/noir)
* [Snapcraft](https://snapcraft.io/noir)
* [Docker (GHCR)](https://github.com/owasp-noir/noir/pkgs/container/noir)

### Code Repository
* [Code Repository](https://github.com/owasp-noir/noir)
* [Discussions](https://github.com/orgs/owasp-noir/discussions)

### Recent Releases

<ul>
    {% for version in site.data.release.versions %}
    <li><a target="_blank" href="https://github.com/owasp-noir/noir/releases/tag/{{version}}">{{ version }}</a></li>
    {% endfor %}
</ul>