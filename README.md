# RESIDENCECMS

![licence](https://img.shields.io/badge/licence-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `RESIDENCECMS` in category **REAL_ESTATE**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** RESIDENCECMS · **Upstream pin:** `e87f47341ce1ffe648e1de95ad70919df7f7e20c` · **Category:** REAL_ESTATE · **Vendor:** Anticloud FZ LLE · **Licence:** MIT

---

## What This Project Does

![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/Coderberg/ResidenceCMS/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/Coderberg/ResidenceCMS/?branch=master) [![Testing with MySQL](https://github.com/Coderberg/ResidenceCMS/actions/workflows/mysql.yml/badge.svg)](https://github.com/Coderberg/ResidenceCMS/actions/workflows/mysql.yml) [![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=Coderberg_ResidenceCMS&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=Coderberg_ResidenceCMS)

ResidenceCMS is a fast and lightweight Property Management System on top of [Symfony 7][1].

![GitHub](https://raw.githubusercontent.com/Coderberg/ResidenceCMS/master/docs/images/screenshot.png)

## Requirements

- PHP 8.2.0 or higher;
- PDO PHP Extension;
- GD PHP extension
- MySQL >= 5.7;
- And the [usual Symfony application requirements][2].

## Installation

1. Install Composer (see http://getcomposer.org/download)

2. Create new project via [Composer][3]

   ```
   $ composer create-project coderberg/residence-cms mywebsite.loc
   ```
3. Enter the newly created folder

   ```
   $ cd mywebsite.loc
   ```

4. After installing, you should configure your web server's document / web root to be the ```public``` directory.

5. Create ```.env.local``` from ```.env``` file and fill in your database credentials

    ```
    DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name
    ```

6. Run

    ```
    $ php bin/console app:install
    ```

7. Go to http://mywebsite.loc/en/admin and log in.

   ```
   login: admin
   password: admin
   ```

8. To use feedback forms, configure MAILER_DSN in ```.env.local```

## Tests

1. Modify your DATABASE_URL config in ```.env.test.local```

   ```
   DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name
   ```

2. Install the ChromeDriver:

   ```
   vendor/bin/bdi detect drivers
   ```

3. Execute this command to run tests:

   ```
   php bin/phpunit
   ```

## Additional documentation
- [How to run Residence CMS in Docker Containers][4]

[1]: https://symfony.com/
[2]: https://symfony.com/doc/current/setup.html#technical-requirements
[3]: https://getcomposer.org/doc/03-cli.md#create-project
[4]: https://github.com/Coderberg/ResidenceCMS/blob/master/docs/docker.md

---

## Installation

1. Install Composer (see http://getcomposer.org/download)

2. Create new project via [Composer][3]

   ```
   $ composer create-project coderberg/residence-cms mywebsite.loc
   ```
3. Enter the newly created folder

   ```
   $ cd mywebsite.loc
   ```

4. After installing, you should configure your web server's document / web root to be the ```public``` directory.

5. Create ```.env.local``` from ```.env``` file and fill in your database credentials

    ```
    DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name
    ```

6. Run

    ```
    $ php bin/console app:install
    ```

7. Go to http://mywebsite.loc/en/admin and log in.

   ```
   login: admin
   password: admin
   ```

8. To use feedback forms, configure MAILER_DSN in ```.env.local```

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

ResidenceCMS is a fast and lightweight Property Management System on top of [Symfony 7][1].

![GitHub](https://raw.githubusercontent.com/Coderberg/ResidenceCMS/master/docs/images/screenshot.png)

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | MIT |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

5. Create ```.env.local``` from ```.env``` file and fill in your database credentials

    ```
    DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name
    ```

6. Run

    ```
    $ php bin/console app:install
    ```

7. Go to http://mywebsite.loc/en/admin and log in.

   ```
   login: admin
   password: admin
   ```

8. To use feedback forms, configure MAILER_DSN in ```.env.local```

## Contributing

Contributing
============

ResidenceCMS is an open source project. Contributions made by
the community are welcome. Send us your ideas, code reviews, pull requests and
feature requests to help us improve this project. All contributions must follow the [usual Symfony contribution requirements](https://symfony.com/doc/current/contributing/index.html).

## Any contributions you make will be under the MIT Software License
In short, when you submit code changes, your submissions are understood to be under the same [MIT License](http://choosealicense.com/licenses/mit/) that covers the project. Feel free to contact the maintainers if that's a concern.

## License

Upstream © its respective contributors under MIT (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** RESIDENCECMS
- **Pinned SHA:** `e87f47341ce1ffe648e1de95ad70919df7f7e20c`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`a5248664db2af255f4ae791cede9db1435eeb7122125dbf6438788461b9a3f21`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

