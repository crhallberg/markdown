# Markdown Documents

A place to keep all of my Markdown beautification projects.

## Complete

| RPG SRD        | CREATOR                | SOURCE                   | LICENSE                       |
| -------------- | ---------------------- | ------------------------ | ----------------------------- |
| Black Flag SRD | [Kobold Press][pub-kp] | [Source: BFRD][src-bfrd] | [ORC license][lic-orc-kobold] |

## In-Progress

| RPG SRD                                                 | CREATOR                   | SOURCE                                        | LICENSE                                                        |
| ------------------------------------------------------- | ------------------------- | --------------------------------------------- | -------------------------------------------------------------- |
| Basic Fantasy Role-Playing Game Core Rules, 4th Edition | [Chris Gonnerman][pub-cg] | [Source: BFRPG][src-bfrpg]                    | [CC-BY-SA 4.0][lic-cc-by-sa]                                   |
| Basic Roleplaying ORC Content Document                  | [Chaosium][pub-chaos]     | [Source: BRP: Universal Game Engine][src-brp] | [ORC license][lic-orc-chaosium]                                |
| Cities Without Number SRD                               | [Kevin Crawford][pub-kc]  | [Source: CWN SRD][src-cwnsrd]                 | [CC0][lic-cc0]                                                 |
| Level-Up Advanced 5e SRD                                | [EN Publishing][pub-en]   | [Source: A5ESRD][src-a5esrd]                  | [CC-BY 4.0][lic-cc-by], [OGL][lic-ogl-a5e], [ORC][lic-orc-a5e] |

## Standards

### [markdownlint](https://github.com/DavidAnson/markdownlint)

I use `markdownlint` through [VSCodium](https://github.com/VSCodium/vscodium) for enforced normalization.

For RPG products, I adjust these rules:

- **[MD024](https://github.com/DavidAnson/markdownlint/blob/main/doc/md024.md):** siblings_only=true (Actions, Actions, Actions)
- **[MD036](https://github.com/DavidAnson/markdownlint/blob/main/doc/md036.md):** false (stat blocks use italics for creature type, magic item properties, etc.)

### [Prettier](https:/prettier.io)

I use Prettier through [VSCodium](https://github.com/VSCodium/vscodium) for automatic formatting.

### Tables

1. Header row should be UPPER CASE.
2. Columns with numbers should be right-aligned with `--:`. Does not apply to columns that contain enough inconsistent text to allow good alignment.
3. Headings that contain only tables should be prefixed with "Table: "

[lic-cc0]: https://creativecommons.org/publicdomain/zero/1.0/
[lic-cc-by]: https://creativecommons.org/licenses/by/4.0/
[lic-cc-by-sa]: https://creativecommons.org/licenses/by-sa/4.0/
[lic-ogl-a5e]: https://a5esrd.com/s/ogl_1oa_lu_a5e_11.pdf
[lic-orc-a5e]: https://a5esrd.com/a5esrd "ORC Notice at bottom of this page"
[lic-orc-chaosium]: https://www.chaosium.com/orclicense
[lic-orc-kobold]: https://koboldpress.com/wp-content/uploads/2023/09/ORC-License.FINAL_.pdf
[pub-cg]: https://www.gonnerman.org/
[pub-chaos]: https://www.chaosium.com/
[pub-en]: https://enpublishingrpg.com/
[pub-kc]: https://sine-nomine-publishing.myshopify.com/
[pub-kp]: https://koboldpress.com/
[src-a5esrd]: https://a5esrd.com/
[src-bfrd]: https://koboldpress.com/black-flag-reference-document/
[src-bfrpg]: https://www.basicfantasy.org/downloads.html#sn_rules
[src-brp]: https://www.chaosium.com/basic-roleplaying-universal-game-engine-pdf/
[src-cwnsrd]: https://www.drivethrurpg.com/en/product/452790/cities-without-number-system-reference-document
