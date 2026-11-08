# K_PYSERIAL

## 1. WHAT — K_PYSERIAL (TIER_9_ROBOTICS_IOT)

K_PYSERIAL is a first-party Anticloud component in TIER_9_ROBOTICS_IOT. It is developed in this repository (no third-party upstream); the source of truth is the code in this directory.
Scanned source: 312 code/text files, ~34173 lines. Dominant extensions: {'.md': 159, '.json': 55, '.py': 92, '.yaml': 2, '.toml': 3, '.sh': 1}.
Key entry points / manifests: anticloud\cli.py, UPSTREAM\pyproject.toml, UPSTREAM\requirements\docs\pyproject.toml, UPSTREAM\requirements\test\pyproject.toml.
Representative files:
- `00_README.md`
- `BENCH.json`
- `DATA_ROOM_INDEX.md`
- `README.md`
- `sbom.cdx.json`
- `01_INVESTOR_PACKAGE\CAP_TABLE.md`
- `01_INVESTOR_PACKAGE\FINANCIAL_MODEL.md`
- `01_INVESTOR_PACKAGE\GTM_STRATEGY.md`
- `01_INVESTOR_PACKAGE\HIRING_PLAN.md`
- `01_INVESTOR_PACKAGE\IP_ASSIGNMENT.md`
- `01_INVESTOR_PACKAGE\USE_OF_FUNDS.md`
- `02_COMMITMENT_TO_SOCIETY\COMMITMENT_TO_SOCIETY.md`
- `03_COMMITMENT_TO_HUMANITY\COMMITMENT_TO_HUMANITY.md`
- `04_COMMITMENT_TO_ENVIRONMENT\COMMITMENT_TO_ENVIRONMENT.md`
- `05_COMMITMENTS_TO_PAST_PRESENT_FUTURE\COMMITMENTS_TO_PAST_PRESENT_FUTURE.md`

## 2. INSTALL

```bash
# inspect source
ls "K_PYSERIAL"
pip install -e .
```

## 3. USE

```bash
python anticloud/cli.py --help
```

## 4. API

Top-level Python imports observed in source (first 60 lines per file):
- `from .gcounter import GCounter`
- `from .lww import HybridLogicalClock, LWWRegister`
- `from .orset import ORSet`
- `from .pncounter import PNCounter`
- `from .tools import miniterm`
- `from __future__ import absolute_import`
- `from __future__ import annotations`
- `from __future__ import print_function`
- `from anticloud_ref._version import __version__`
- `from anticloud_ref._version import __version__, version_tuple`
- `from anticloud_ref.bench.compliance import (`
- `from anticloud_ref.bench.runner import (`
- `from anticloud_ref.bench.sbom import build_sbom, write_sbom`
- `from anticloud_ref.crdt import (`
- `from anticloud_ref.crdt.convergence import (`
- `from anticloud_ref.crdt.convergence import convergence_report`
- `from anticloud_ref.crdt.gcounter import GCounter`
- `from anticloud_ref.crdt.lww import HybridLogicalClock, LWWRegister, Timestamp`
- `from anticloud_ref.crdt.orset import ORSet`
- `from anticloud_ref.crdt.pncounter import PNCounter`

## 5. DEPENDENCIES

Extensions histogram: {".md": 159, ".json": 55, ".py": 92, ".yaml": 2, ".toml": 3, ".sh": 1}. Manifests detected: anticloud\cli.py, UPSTREAM\pyproject.toml, UPSTREAM\requirements\docs\pyproject.toml, UPSTREAM\requirements\test\pyproject.toml.

## 6. CONFIGURE

Environment variables and config files are read from source defaults; no mandatory external config was detected by the scan. Check the entry-point files above for env-var names. Common pattern: copy any `*.example` / `config.*` file next to the entry point and edit values.

## 7. CONTRIBUTING

First-party repo: open an issue describing the change, keep patches small, add/extend tests next to the module, and ensure the 16-check suite stays green before submitting.

## 8. LICENSE — Anticommons 0.1.0

This first-party component is released under the Anticommons 0.1.0 license. See LICENSE (or LICENCE) in the repository root; if absent, the Anticommons 0.1.0 terms apply as stated by the project owner.

## 9. UPSTREAM — first-party (no third-party upstream)

First-party Anticloud work: there is no third-party upstream clone for this project. Provenance is the local change history of this directory, not a pinned external SHA.

## 10. BENCHMARKS (from on-disk BENCH.json)

BENCH.json present on disk. Excerpt: `{"schema": "anticloud.tier-bench/1", "project": "K_PYSERIAL", "source": {"repo_path": "E:\\fenta\\Downloads\\The Anticloud\\TIER_9_ROBOTICS_IOT\\K_PYSERIAL\\UPSTREAM", "git": {"head": "a5c48d445fbc1943d4fabf8d9090a50fda3172fd", "url": "https://github.com/pyserial/pyserial", "branch": "master", "committed_at": "2024-04-09T16:24:59+08:00"}}, "metrics": {"files_total": 88, "source_files_scanned": 57, "lines_of_code": 12468, "languages": {".py": 59, ".rst": 12, ".txt": 4, ".toml": 3, "(none)": 2, ".wxg": 2, ".yaml": 1, ".in": 1, ".cfg": 1, ".ini": 1, ".sh": 1, ".png": 1}}, "licence": {"spdx": "BSD-3-Clause", "class": "A", "source_file": "LICENSE.txt", "redistribution_allowed": true}, "dependencies": {"count": 2, "unique": 2, "by_ecosystem": {"pypi": 2}, "list": [{"ecosystem": "pypi", "name": "sphinx", "version": "", "source_file": "requirements/docs/pyproject.toml", "raw": "sphinx"}, {"ecosystem": "pypi", "name": "sphinx_rtd_theme", "version": "", "source_file": "requirements/docs/pyproject.toml", "raw": "sphinx_rtd_theme"}]}, "owasp_top10": {"total_findings": 20, "files_with_findings": 15, "severity": {"high": 0, "medium": 3, "low": 17}, "categories": {"A01-BrokenAccessControl": {"cou`
File/LOC scan at doc time: 312 files, ~34173 lines. Result register (ISOLATED_LAB_RESULTS/03_Result_Register.md): present; anticloud/ overlay entries: 16; installer/ dir: present.

## Appendix — full scanned file list (evidence)

- `00_README.md`
- `BENCH.json`
- `DATA_ROOM_INDEX.md`
- `README.md`
- `sbom.cdx.json`
- `01_INVESTOR_PACKAGE\CAP_TABLE.md`
- `01_INVESTOR_PACKAGE\FINANCIAL_MODEL.md`
- `01_INVESTOR_PACKAGE\GTM_STRATEGY.md`
- `01_INVESTOR_PACKAGE\HIRING_PLAN.md`
- `01_INVESTOR_PACKAGE\IP_ASSIGNMENT.md`
- `01_INVESTOR_PACKAGE\USE_OF_FUNDS.md`
- `02_COMMITMENT_TO_SOCIETY\COMMITMENT_TO_SOCIETY.md`
- `03_COMMITMENT_TO_HUMANITY\COMMITMENT_TO_HUMANITY.md`
- `04_COMMITMENT_TO_ENVIRONMENT\COMMITMENT_TO_ENVIRONMENT.md`
- `05_COMMITMENTS_TO_PAST_PRESENT_FUTURE\COMMITMENTS_TO_PAST_PRESENT_FUTURE.md`
- `06_WHITELABELLING_AND_REPACKAGING\WHITELABELLING_AND_REPACKAGING.md`
- `07_ENTERPRISE_LICENSE_AND_PRICING\ENTERPRISE_LICENSE_AND_PRICING.md`
- `08_INTELLECTUAL_PROPERTY_AND_RIGHTS\INTELLECTUAL_PROPERTY_AND_RIGHTS.md`
- `09_COMPLIANCE\COMPLIANCE.md`
- `10_TECHNICAL_HANDOFF\TECHNICAL_HANDOFF.md`
- `11_TUTORIAL_DEVELOPERS\TUTORIAL_DEVELOPERS.md`
- `12_TUTORIAL_ENTERPRISE\TUTORIAL_ENTERPRISE.md`
- `13_TUTORIAL_USERS\TUTORIAL_USERS.md`
- `14_DEVELOPER_COOKBOOKS\DEVELOPER_COOKBOOKS.md`
- `15_DISASTER_RECOVERY\DISASTER_RECOVERY.md`
- `16_VULNERABILITY_MANAGEMENT\VULNERABILITY_MANAGEMENT.md`
- `17_HOW_TO_UPDATE\HOW_TO_UPDATE.md`
- `18_COMMAND_LINE_INTERFACE\COMMAND_LINE_INTERFACE.md`
- `19_SYSTEM_OF_THINGS_SOT\SYSTEM_OF_THINGS_SOT.md`
- `20_ACADEMIC_RESEARCH\ACADEMIC_RESEARCH.md`
- `21_RELATED_SCIENTIFIC_RESEARCH\RELATED_SCIENTIFIC_RESEARCH.md`
- `22_INDEPENDENT_INSURANCE\INDEPENDENT_INSURANCE.md`
- `23_HOW_TO_CITE\HOW_TO_CITE.md`
- `24_ANTICOMMONS_LICENSE\ANTICOMMONS_LICENSE.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\MILLENNIUM_PROBLEM_PROPOSALS.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\HQ_ARCHIVE\HQ_manifest.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P01\P01.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P01\P01.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P02\P02.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P02\P02.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P03\P03.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P03\P03.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P04\P04.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P04\P04.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P04\P04_HQ_solution.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P04\P04_HQ_solution.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P05\P05.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P05\P05.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P06\P06.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P06\P06.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P07\P07.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P07\P07.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P08\P08.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P08\P08.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P09\P09.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P09\P09.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P09\P09_HQ_solution.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P09\P09_HQ_solution.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P10\P10.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P10\P10.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P11\P11.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P11\P11.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P12\P12.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P12\P12.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P13\P13.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P13\P13.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P14\P14.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P14\P14.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P15\P15.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P15\P15.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P16\P16.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P16\P16.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P17\P17.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P17\P17.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P18\P18.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P18\P18.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P19\P19.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P19\P19.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P20\P20.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P20\P20.md`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P20\P20_HQ_solution.json`
- `25_MILLENNIUM_PROBLEM_PROPOSALS\P20\P20_HQ_solution.md`
- `26_INTEGRATIONS_AND_SDK\INTEGRATIONS_AND_SDK.md`
- `27_DEPENDENCIES\DEPENDENCIES.md`
- `28_TECHNICAL_WHITEPAPER\TECHNICAL_WHITEPAPER.md`
- `29_INVESTOR_MEMO\29_INVESTOR_MEMO.md`
- `30_LOI\ENTERPRISE_LOI.md`
- `30_LOI\GENERAL_LOI.md`
- `31_UNIT_ECONOMICS\31_UNIT_ECONOMICS.md`
- `32_CONTRACTS\CONTRACT_100M.md`
- `32_CONTRACTS\CONTRACT_10M.md`
- `32_CONTRACTS\CONTRACT_1M.md`
- `32_CONTRACTS\CONTRACT_5M.md`
- `32_CONTRACTS\CONTRACT_80M.md`
- `32_CONTRACTS\CONTRACT_8M.md`
- `33_COMPETITIVE_MOAT\33_COMPETITIVE_MOAT.md`
- `34_FOUNDER_PROFILE\FOUNDER_PROFILE.md`
- `35_INVESTOR_FAQ\INVESTOR_FAQ.md`
- `36_ADVISORY_BOARD\ADVISORY_BOARD.md`
- `anticloud\cli.py`
- `anticloud\crdt.py`
- `anticloud\observability.py`
- `anticloud\provenance.py`
- `anticloud\single_binary.py`
- `anticloud\sovereign_memory.py`
- `anticloud\zero_trust.py`
- `anticloud\_version.py`
- `anticloud\__init__.py`
- `anticloud\bench\compliance.py`
- `anticloud\bench\runner.py`
- `anticloud\bench\sbom.py`
- `anticloud\bench\__init__.py`
- `anticloud\crdt\convergence.py`
- `anticloud\crdt\gcounter.py`
- `anticloud\crdt\lww.py`
- `anticloud\crdt\orset.py`
- `anticloud\crdt\pncounter.py`
- `anticloud\crdt\__init__.py`
- `anticloud\deps\lock.py`
- `anticloud\deps\__init__.py`
- `anticloud\licence\classifier.py`
- `anticloud\licence\policy.py`
- `anticloud\licence\__init__.py`
- `anticloud\perf\harness.py`
- `anticloud\perf\__init__.py`
- `anticloud\provenance\chain.py`
- `anticloud\provenance\__init__.py`
- `anticloud\security\safeio.py`
- `anticloud\security\secrets.py`
- `anticloud\security\validators.py`
- `anticloud\security\vault.py`
- `anticloud\security\__init__.py`
- `BRANDING\brand.md`
- `DEVELOPMENT\01_Build_And_Test.md`
- `DEVELOPMENT\02_Architecture.md`
- `DEVELOPMENT\03_Extension_Guide.md`
- `docs\01_INVESTOR_PACKAGE\README.md`
- `docs\02_COMMITMENT_TO_SOCIETY\README.md`
- `docs\03_COMMITMENT_TO_HUMANITY\README.md`
- `docs\04_COMMITMENT_TO_ENVIRONMENT\README.md`
- `docs\05_COMMITMENTS_TO_PAST_PRESENT_FUTURE\README.md`
- `docs\06_WHITELABELLING_AND_REPACKAGING\README.md`
- `docs\07_ENTERPRISE_LICENSE_AND_PRICING\README.md`
- `docs\08_INTELLECTUAL_PROPERTY_AND_RIGHTS\README.md`
- `docs\09_COMPLIANCE\README.md`
- `docs\10_TECHNICAL_HANDOFF\README.md`
- `docs\11_TUTORIAL_DEVELOPERS\README.md`
- `docs\12_TUTORIAL_ENTERPRISE\README.md`
- `docs\13_TUTORIAL_USERS\README.md`
- `docs\14_DEVELOPER_COOKBOOKS\README.md`
- `docs\15_DISASTER_RECOVERY\README.md`
- `docs\16_VULNERABILITY_MANAGEMENT\README.md`
- `docs\17_HOW_TO_UPDATE\README.md`
- `docs\18_COMMAND_LINE_INTERFACE\README.md`
- `docs\19_SYSTEM_OF_THINGS_SOT\README.md`
- `docs\20_ACADEMIC_RESEARCH\README.md`
- `docs\21_RELATED_SCIENTIFIC_RESEARCH\README.md`
- `docs\22_INDEPENDENT_INSURANCE\README.md`
- `docs\23_HOW_TO_CITE\README.md`
- `docs\24_ANTICOMMONS_LICENSE\README.md`
- `docs\25_MILLENNIUM_PROBLEM_PROPOSALS\README.md`
- `docs\26_INTEGRATIONS_AND_SDK\README.md`
- `docs\27_DEPENDENCIES\README.md`
- `docs\28_TECHNICAL_WHITEPAPER\README.md`
- `docs\29_INVESTOR_MEMO\README.md`
- `docs\30_LOI\README.md`
- `Environment_Lab_Results\raw_metrics.json`
- `Environment_Lab_Results\README.md`
- `installer\license.md`
- `installer\loi.md`
- `installer\tauri.conf.json`
- `ISOLATED_LAB_RESULTS\01_Reproduction.md`
- `ISOLATED_LAB_RESULTS\02_Environment.md`
- `ISOLATED_LAB_RESULTS\03_Result_Register.md`
- `L5_L2_Classification\classification.md`
- `L5_L2_Classification\deploy_guide.md`
- `L5_L2_Classification\developer_cookbook.md`
- `L5_L2_Classification\HOW_TO_OPERATE.md`
- `L5_L2_Classification\HOW_TO_UPDATE.md`
- `L5_L2_Classification\PROTOCOLS.md`
- `OFFICIAL_BENCHMARKS\01_FedRAMP.md`
- `OFFICIAL_BENCHMARKS\02_SOC2.md`
- `OFFICIAL_BENCHMARKS\03_SOC1.md`
- `OFFICIAL_BENCHMARKS\04_COMPREHENSIVE_BENCHMARKS.json`
- `OFFICIAL_BENCHMARKS\04_PAX_Results.md`
- `OFFICIAL_BENCHMARKS\05_OWASP.md`
- `OFFICIAL_BENCHMARKS\06_CRDT.md`
- `OFFICIAL_BENCHMARKS\07_Provenance.md`
- `OFFICIAL_BENCHMARKS\08_ZeroTrust.md`
- `OFFICIAL_BENCHMARKS\09_Observability.md`
- `OFFICIAL_BENCHMARKS\10_SovereignMemory.md`
- `OFFICIAL_BENCHMARKS\11_DeterministicBuild.md`
- `OFFICIAL_BENCHMARKS\01_FedRAMP\01_FedRAMP.json`
- `OFFICIAL_BENCHMARKS\01_FedRAMP\01_FedRAMP.md`
- `OFFICIAL_BENCHMARKS\02_SOC2_TypeII\02_SOC2_TypeII.json`
- `OFFICIAL_BENCHMARKS\02_SOC2_TypeII\02_SOC2_TypeII.md`
- `OFFICIAL_BENCHMARKS\03_SOC1_TypeII\03_SOC1_TypeII.json`
- `OFFICIAL_BENCHMARKS\03_SOC1_TypeII\03_SOC1_TypeII.md`
- `OFFICIAL_BENCHMARKS\04_NIST_AI_RMF\04_NIST_AI_RMF.json`
- `OFFICIAL_BENCHMARKS\04_NIST_AI_RMF\04_NIST_AI_RMF.md`
- `OFFICIAL_BENCHMARKS\05_NIST_SP800_53\05_NIST_SP800_53.json`
- `OFFICIAL_BENCHMARKS\05_NIST_SP800_53\05_NIST_SP800_53.md`
- `OFFICIAL_BENCHMARKS\06_NIST_CSFW\06_NIST_CSFW.json`
- `OFFICIAL_BENCHMARKS\06_NIST_CSFW\06_NIST_CSFW.md`
- `OFFICIAL_BENCHMARKS\07_ISO_27001\07_ISO_27001.json`
- `OFFICIAL_BENCHMARKS\07_ISO_27001\07_ISO_27001.md`
- `OFFICIAL_BENCHMARKS\08_OWASP_LLM_Top10\08_OWASP_LLM_Top10.json`
- `OFFICIAL_BENCHMARKS\08_OWASP_LLM_Top10\08_OWASP_LLM_Top10.md`
- `OFFICIAL_BENCHMARKS\09_OWASP_Top10\09_OWASP_Top10.json`
- `OFFICIAL_BENCHMARKS\09_OWASP_Top10\09_OWASP_Top10.md`
- `OFFICIAL_BENCHMARKS\10_HIPAA\10_HIPAA.json`
- `OFFICIAL_BENCHMARKS\10_HIPAA\10_HIPAA.md`
- `OFFICIAL_BENCHMARKS\11_PCI_DSS\11_PCI_DSS.json`
- `OFFICIAL_BENCHMARKS\11_PCI_DSS\11_PCI_DSS.md`
- `OFFICIAL_BENCHMARKS\12_CMMC_2\12_CMMC_2.json`
- `OFFICIAL_BENCHMARKS\12_CMMC_2\12_CMMC_2.md`
- `OFFICIAL_BENCHMARKS\13_FISMA\13_FISMA.json`
- `OFFICIAL_BENCHMARKS\13_FISMA\13_FISMA.md`
- `OFFICIAL_BENCHMARKS\14_FIPS_140_3\14_FIPS_140_3.json`
- `OFFICIAL_BENCHMARKS\14_FIPS_140_3\14_FIPS_140_3.md`
- `OFFICIAL_BENCHMARKS\15_GDPR\15_GDPR.json`
- `OFFICIAL_BENCHMARKS\15_GDPR\15_GDPR.md`
- `OFFICIAL_BENCHMARKS\16_HITRUST_CSF\16_HITRUST_CSF.json`
- `OFFICIAL_BENCHMARKS\16_HITRUST_CSF\16_HITRUST_CSF.md`
- `OFFICIAL_BENCHMARKS\17_TISAX\17_TISAX.json`
- `OFFICIAL_BENCHMARKS\17_TISAX\17_TISAX.md`
- `OFFICIAL_BENCHMARKS\18_DORA\18_DORA.json`
- `OFFICIAL_BENCHMARKS\18_DORA\18_DORA.md`
- `OFFICIAL_BENCHMARKS\19_SOX_ITGC\19_SOX_ITGC.json`
- `OFFICIAL_BENCHMARKS\19_SOX_ITGC\19_SOX_ITGC.md`
- `OFFICIAL_BENCHMARKS\20_COBIT_2019\20_COBIT_2019.json`
- `OFFICIAL_BENCHMARKS\20_COBIT_2019\20_COBIT_2019.md`
- `OFFICIAL_BENCHMARKS\21_SLSA_L3\21_SLSA_L3.json`
- `OFFICIAL_BENCHMARKS\21_SLSA_L3\21_SLSA_L3.md`
- `OFFICIAL_BENCHMARKS\22_SSDF\22_SSDF.json`
- `OFFICIAL_BENCHMARKS\22_SSDF\22_SSDF.md`
- `OFFICIAL_BENCHMARKS\23_SBOM\23_SBOM.json`
- `OFFICIAL_BENCHMARKS\23_SBOM\23_SBOM.md`
- `OFFICIAL_BENCHMARKS\24_MITRE_ATTCK\24_MITRE_ATTCK.json`
- `OFFICIAL_BENCHMARKS\24_MITRE_ATTCK\24_MITRE_ATTCK.md`
- `OFFICIAL_BENCHMARKS\25_CVSS_v4\25_CVSS_v4.json`
- `OFFICIAL_BENCHMARKS\25_CVSS_v4\25_CVSS_v4.md`
- `OFFICIAL_BENCHMARKS\26_TRL_ML\26_TRL_ML.json`
- `OFFICIAL_BENCHMARKS\26_TRL_ML\26_TRL_ML.md`
- `TECHNICAL\01_Architecture.md`
- `TECHNICAL\02_Upstream_Provenance.md`
- `TECHNICAL\03_Verification.md`
- `UPSTREAM\.readthedocs.yaml`
- `UPSTREAM\pyproject.toml`
- `UPSTREAM\.github\workflows\test.yaml`
- `UPSTREAM\documentation\conf.py`
- `UPSTREAM\examples\at_protocol.py`
- `UPSTREAM\examples\port_publisher.py`
- `UPSTREAM\examples\port_publisher.sh`
- `UPSTREAM\examples\rfc2217_server.py`
- `UPSTREAM\examples\setup-miniterm-py2exe.py`
- `UPSTREAM\examples\setup-rfc2217_server-py2exe.py`
- `UPSTREAM\examples\setup-wxTerminal-py2exe.py`
- `UPSTREAM\examples\tcp_serial_redirect.py`
- `UPSTREAM\examples\wxSerialConfigDialog.py`
- `UPSTREAM\examples\wxTerminal.py`
- `UPSTREAM\requirements\docs\pyproject.toml`
- `UPSTREAM\requirements\test\pyproject.toml`
- `UPSTREAM\serial\rfc2217.py`
- `UPSTREAM\serial\rs485.py`
- `UPSTREAM\serial\serialposix.py`
- `UPSTREAM\serial\serialutil.py`
- `UPSTREAM\serial\serialwin32.py`
- `UPSTREAM\serial\win32.py`
- `UPSTREAM\serial\__init__.py`
- `UPSTREAM\serial\__main__.py`
- `UPSTREAM\serial\threaded\__init__.py`
- `UPSTREAM\serial\tools\hexlify_codec.py`
- `UPSTREAM\serial\tools\list_ports.py`
- `UPSTREAM\serial\tools\list_ports_common.py`
- `UPSTREAM\serial\tools\list_ports_linux.py`
- `UPSTREAM\serial\tools\list_ports_osx.py`
- `UPSTREAM\serial\tools\list_ports_posix.py`
- `UPSTREAM\serial\tools\list_ports_windows.py`
- `UPSTREAM\serial\tools\miniterm.py`
- `UPSTREAM\serial\tools\__init__.py`
- `UPSTREAM\serial\urlhandler\protocol_alt.py`
- `UPSTREAM\serial\urlhandler\protocol_cp2110.py`
- `UPSTREAM\serial\urlhandler\protocol_hwgrep.py`
- `UPSTREAM\serial\urlhandler\protocol_loop.py`
- `UPSTREAM\serial\urlhandler\protocol_rfc2217.py`
- `UPSTREAM\serial\urlhandler\protocol_socket.py`
- `UPSTREAM\serial\urlhandler\protocol_spy.py`
- `UPSTREAM\serial\urlhandler\__init__.py`
- `UPSTREAM\test\run_all_tests.py`
- `UPSTREAM\test\test.py`
- `UPSTREAM\test\test_advanced.py`
- `UPSTREAM\test\test_cancel.py`
- `UPSTREAM\test\test_close.py`
- `UPSTREAM\test\test_context.py`
- `UPSTREAM\test\test_exclusive.py`
- `UPSTREAM\test\test_hexlify_code.py`
- `UPSTREAM\test\test_high_load.py`
- `UPSTREAM\test\test_iolib.py`
- `UPSTREAM\test\test_pty.py`
