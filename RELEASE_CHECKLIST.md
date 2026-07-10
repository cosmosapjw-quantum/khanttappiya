# Stage20-014 GitHub Release + Zenodo checklist

## A. Repository files

- [x] Root `LICENSE.txt`: official CC BY 4.0 legal code
- [x] `LICENSE_SCOPE.md`
- [x] `README.md`
- [x] `RIGHTS_AND_ACCESS_STATUS.md`
- [x] `CITATION.cff`
- [x] `CITATION.bib`
- [x] `.zenodo.json`
- [x] `RELEASE_RECORD.json`
- [x] `SHA256SUMS_ORIGINAL_RELEASE.txt`
- [ ] Upload `public-core/examples/KKY_RC3_9_EXAMPLE_BANK.csv`
- [ ] Upload `public-core/examples/KKY_RC3_9_NEGATIVE_APPENDIX.csv`

## B. GitHub Release

- [ ] Confirm repository slug policy: keep `khanttappiya`, while canonical title remains `Kkanttappiya`
- [ ] Enable the repository in Zenodo GitHub integration before publishing the release
- [ ] Create Git tag `rc3.9`
- [ ] Create GitHub Release `Kkanttappiya RC3.9`
- [ ] Attach `KKY_RC3_9_STAGE20_012A_RELEASE_FREEZE_20260710.zip`
- [ ] Attach `KKY_RC3_9_STAGE20_012A_LEARNER_PUBLIC_CORE_RELEASE_20260710.zip`
- [ ] Optionally attach `KKY_RC3_9_STAGE20_013_CANONICAL_ARCHIVE_BAG_20260710.zip`

## C. Integrity anchors

- Full release ZIP: `037080ce6f72268c6462cbd905853ba52dd754b6ae1378dbb8fe58e2f9e059a3`
- Learner public-core ZIP: `865dbfb8757f31cbf5829735a28e9c12cd5091c626f5d527b3a3bda0e7a008b3`
- BagIt archive ZIP: `e4aae40cd92596bef041049656acc2f2af5e04a9588a94583d2fa24aed36ab6f`

## D. Zenodo / archive closure

- [ ] Confirm Zenodo ingested the `rc3.9` release
- [ ] Record version-specific DOI and record URL
- [ ] Verify archived file checksums against the values above
- [ ] Update repository-level README and `RELEASE_RECORD.json` with DOI; do not rebuild frozen ZIPs
- [ ] Mark Stage20-014 archive/publication gate closed

## E. Next branch

Only after section D passes, open Stage21-001 as a separate expansion branch. Do not edit the frozen RC3.9 payload.
