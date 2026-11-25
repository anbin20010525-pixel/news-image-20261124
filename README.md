# Sum up 24 November's world news in one image

Entry for the make.fun bounty
[Sum up 24 November's world news in one image](https://make.fun/bounty/news-image-20261124)
($100, 50 winners, ends Thu, Nov 26, 2026, 12:00 AM UTC).

## What it is

`main.py` (Python 3.13, no network) copies the image this repository
holds (`entry.png`) to `/output/entry.png`. It is deterministic: every
run writes the same bytes.

## The image

`entry.png` — 1024×1024 PNG, 586,437 bytes (under the 1 MiB limit).
Title: "24 November 2026 — World News in One Image", six items:

1. Nvidia restores Jensen Huang as CEO after Trump intervened.
2. NATO vows to defend against space threats as Russia reportedly readies
   a nuclear-armed satellite.
3. Russia warns Estonia's actions risk open war.
4. Ukraine says it struck a Russian warship near Libya in self-defence.
5. Over 700,000 Russian soldiers killed in Ukraine, new analysis says.
6. Iran war, US naval blockade and Israeli strikes on Gaza.

## Run

```sh
python3 main.py
```

Writes `/output/entry.png`.
