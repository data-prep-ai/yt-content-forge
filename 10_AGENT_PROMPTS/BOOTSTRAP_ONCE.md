# MUSE MASTER BOOTSTRAP — RUN ONCE IN A CLEAN WORKSPACE

You are not being asked to make a video yet.

You are being asked to ingest and prepare a permanent documentary production system.

## 1. Read the system completely

Start with:
- `PRODUCTION_SYSTEM_SPEC.md`
- `README.md`
- `09_SYSTEM/bootstrap/BOOTSTRAP_STATUS.md`
- `09_SYSTEM/bootstrap/BOOTSTRAP_CHECKLIST.md`

Then read the entire repository, including:
- `00_CORE/`
- `01_RESEARCH/`
- `02_CREATIVE_BIBLE/`
- `03_EDITING_ACADEMY/`
- `04_WORKFLOWS/`
- `05_TEMPLATES/`
- `06_PRODUCTION/`
- `07_ASSET_LIBRARY/`
- `08_ANALYTICS/`
- `09_SYSTEM/`
- `10_AGENT_PROMPTS/`

Do not rely on prior chat memory as a source of truth.

## 2. Audit the system

Create a written audit in:
`09_SYSTEM/bootstrap/SYSTEM_AUDIT.md`

Identify:
- contradictions;
- missing tools;
- missing production steps;
- missing asset categories;
- rights/licensing gaps;
- anything that still assumes a human will supply a topic, research, media, or edit instructions;
- any rule that is only an assumption or research gap.

Fix structural problems that can be fixed safely. Do not silently rewrite the Creative Bible or research conclusions.

## 3. Provision the toolchain

Read `09_SYSTEM/bootstrap/TOOLCHAIN_REQUIREMENTS.md`.

Test the real environment. Record actual tools and versions in:
`09_SYSTEM/tooling/TOOLCHAIN_INVENTORY.md`

Do not mark a capability available until it has been tested.

The final system must be able to:
- research the web;
- download permitted media;
- inspect documents/images;
- generate consistent narration;
- create diagrams/maps/2.5D motion/reconstructions;
- construct an actual edit/timeline;
- mix audio;
- render a final video;
- inspect the final output.

Where the environment lacks a capability, install/use an allowed tool if possible. If access requires a paid account, human login, or external approval, record `HUMAN_REQUIRED` instead of attempting to bypass it.

## 4. Build the permanent asset system

Read:
`09_SYSTEM/bootstrap/ASSET_PROVISIONING_PLAN.md`

and
`09_SYSTEM/asset_provisioning/PROVIDER_REGISTRY.md`

Audit the providers and current license terms before downloading anything.

Acquire a curated starter pack for the editing system — not a giant uncontrolled dump.

Prioritize:
- restrained documentary music;
- restrained drones;
- reusable motion/graphic elements;
- maps/diagram components;
- source cards/lower thirds;
- text/date/timeline components;
- lawful reusable fonts;
- other genuinely reusable production assets.

For every retained asset:
- record source URL;
- record license type and scope;
- save the applicable license/receipt/evidence;
- record the asset in `07_ASSET_LIBRARY/ASSET_REGISTRY.csv`;
- record detailed rights in `05_TEMPLATES/LICENSE_LEDGER.csv`.

IMPORTANT:
Do not bypass paywalls, login restrictions, DRM, download limits, or provider terms.
Do not bulk warehouse assets from a provider whose terms prohibit warehousing or automated downloading.
If a source is subscription-scoped, keep it in the project-specific/subscription-scoped workflow.

## 5. Build the reusable production toolkit

Prepare:
- document/source card templates;
- lower thirds;
- date/location labels;
- timeline components;
- map animation components;
- diagram/annotation components;
- archival still treatment;
- disclosed reconstruction treatment;
- caption/title styles;
- audio mixing presets if supported.

Every reusable component must be documented sufficiently that another run can use it without rediscovery.

## 6. Verify the production template

Verify:
`06_PRODUCTION/_TEMPLATE/`

and every template/ledger under `05_TEMPLATES/`.

Ensure a new video can be created without modifying global files unnecessarily.

## 7. Verify state/logging

The system must be able to resume after interruption by reading:
- `CURRENT_STATE.md`
- `TASK_QUEUE.md`
- current project folder
- production log

## 8. Prepare the system, but DO NOT make the demo

The bootstrap run must stop before demo production.

Write:
`09_SYSTEM/bootstrap/BOOTSTRAP_REPORT.md`

Include:
- repository audit summary;
- tool inventory;
- assets acquired/created;
- provider/license decisions;
- limitations;
- human-required actions;
- final readiness judgment.

Only after all critical bootstrap gates pass may you edit:
`09_SYSTEM/bootstrap/BOOTSTRAP_STATUS.md`

and set:
`BOOTSTRAP_COMPLETE: TRUE`

Also update:
`09_SYSTEM/state/CURRENT_STATE.md`

to show the system is ready for the 2-minute autonomous demo.

STOP.
