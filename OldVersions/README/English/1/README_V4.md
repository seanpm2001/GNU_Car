
***

# The GNU Car project

**Proposed by:** [`@seanpm2001`](https://github.com/seanpm2001/)

| <img alt="GNU Car banner failed to load. Click/tap here to attempt to view it" src="/GNU_Car_1080pWallpaper_V1_HighCompression.png" width="853" height="480"/> |
|---|
| **About:** Nobody really puts that much effort into logos anymore, so even though this is a minimal design, it isn't too minimal compared to most logos. |
| The GNU head is centered on the steering wheel |
| I put some ice gradient on the GNU text, I didn't know what else to put. |
| The texture for the word `car` is a fabric texture. I didn't realize this until after I created the image, but the fabric evokes the feeling of an older vacation car, a tropical vibe. I am not too experienced with automobile history, so if someone can help me pinpoint the decade(s) of this trend, that would be nice. |

**Legal disclaimer:** As it currently stands, this project is not endorsed by, or affiliated with the GNU project or the Free Software Foundation, but I would really like it to be, and I will donate this project to them upon their request, provided they can care for and advance the project and eventually achieve the goal.

## Reasoning

All current electric cars are powered by non-free software. I want a car that does not have any Google, Apple, Tesla, or other proprietary bits in it. I want a completely GNU car, made up entirely of free, libre, and open source software. This is the biggest barrier for why I can't start driving yet.

As of 2023, Saturday, February 18th, there is not a single car on the market that meets this goal.

## Guidelines

### General

- The software design of the car MUST follow the [`GNU Philosophy`](https://www.gnu.org/philosophy/philosophy.html) there cannot be a single bit and/or byte of proprietary software in the cars system.

> GNU prerequisites

![DRM-free_label.en.svg](DRM-free_label.en.svg/)

- No proprietary blobs or pieces
- No permissive licensing
- No DRM/TPM
- User must be able to access every byte of source code freely AND
- User must be free to redistribute and modify the operating system in any way they want, as long as it doesn't violate the GPL license

### Licensing

- The car must be licensed under one or more of the following licenses: AGPL2, AGPL3, GPL2, GPL3, LGPL2, or LGPL3. No other licenses are permitted.

### Performance

- The software must be efficient, the operating system should require no more than 512 megabytes of RAM to run idle, even if the car it is being designed for has multiple gigabytes of RAM. Performance is key.

## Candidate systems

Operating system candidates include:

- [Trisquel Linux](https://trisquel.info/) (A certified GNU/Linux operating system)
- Other (list one here)

> **Note** There can be more than 1 operating system that adheres to the GNU car specification. I encourage there to be a choice of more than 1 system

## Common confusion

**But there already are cars with open source software. Doesn't Linux mean open source?**

Currently, yes, there are some cars with operating systems based on Linux. However, just because the kernel is Linux doesn't mean the entire car software suite is open source. Tesla uses Linux in their cars, but their cars contain proprietary software bits and blobs, and also some malicious telemetry.

**Isn't Android open source?**

Android is a freemium operating system that has a variant known as Android auto that runs on cars. Android is based on Linux, but has become proprietary software with strict trademark and usage rules that make it freemium, including major proprietary bits like GMS (Google Mobile Services) and Google Play. Remember that Freemium isn't free.

**GNU/Linux usage**

Most people refer to Linux as just Linux. I am using GNU/Linux here to differentiate it from Linux with proprietary bits (Android, TeslaOS, ChromeOS, ChromiumOS, etc.) The GNU is an assertion that the software follows the Free Software Foundations vision of truly free software.

## Pros

> **Note** This list is incomplete.

- More transparency on the inner working of the car
- Encourages the right to repair
- Promotes both free and open source software

## Cons

- No known cons to list

## Other

### Rejected names

The following names were rejected:

- **GNU Mobile** - Reason: Sounds like a mobile operating system project, rather than an automobile system project.
- **No other rejected names**

### Logo

A logo was created for the project on 2023, Thursday, February 16th. It can be changed in the future when needed.

The logo is of the GNU mascot overlaying a steering wheel. It has 2 variants: one with a wordmark, and one without a wordmark. Both images are transparent, 1024x1024, and were made in GIMP 2.10.30.

| <img alt="GNU Car logo (wordmarked) failed to load. Click/tap here to attempt to view it" src="/GNU_Car_1024pxIcon_V1_HighCompression.png" width="200" height="200"/> | <img alt="GNU Car logo (no wordmark) failed to load. Click/tap here to attempt to view it" src="/GNU_Car_1024pxIcon_No-Wordmark_V1_HighCompression.png" width="200" height="200"/> |
|---|---|
| Wordmark | No wordmark |

### Development

I cannot personally develop the car myself, I have a rule where I can't develop my own automobile software, as I already have too many projects I am working on, and I left this open for others. I can still contribute to existing automobile software, however.

### Hardware

The hardware this software will run on is still a major decision that needs to be made. Flashing an existing car may not be feasible, and producing new hardware may prove to be difficult.

### Competitors

A non-exhaustive list of competitors to this project.

- Google LLC§Android Auto
- Tesla Inc.
- Other/unlisted

> **Note** None of the listed competitors are producing GNU systems in their vehicles.

### Culmination

This idea has been in development for over a year. I finally published it on 2023, Thursday, February 16th, once I came up with a good identifying name (GNU Car) it may not seem like much, but this was an idea that took a lot of time (on and off) to develop. I am hoping that it will expand and grow.

***

### File info

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `4 (2023, Saturday, February 18th at 3:14 pm PST)`

**Line count (including blank lines and compiler line):** `247`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

> **Note** _On 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

> **Note** **You may need special rendering support for the `<details>` HTML tag being used in this document**

***

## File history

<details><summary><p><b>Click/tap here to expand/collapse the file history for this file</b></p></summary>

<details><summary><p><b>Version 1 (2023, Thursday, February 16th at 2:30 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Started the file
- [x] Added the lead section
- [x] Added the `Reasoning` section
- [x] Added the `Guidelines` section
- [x] Added the `Candidate systems` section
- [x] Added the `Other` section
- - [x] Added the `Rejected names` subsection
- - [x] Added the `Logo` subsection
- [x] Added the file version stamp
- [ ] No other changes in version 1

</details>

<details><summary><p><b>Version 2 (2023, Thursday, February 16th at 2:56 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Updated the `Candidate systems` section
- [ ] ...
- - [x] Updated the `Rejected names` subsection
- - [x] Added the `Development` subsection
- - [x] Added the `Hardware` subsection
- - [x] Added the `Competitors` subsection
- [x] Updated the file version stamp
- [ ] No other changes in version 2

</details>

<details><summary><p><b>Version 3 (2023, Thursday, February 16th at 5:44 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Added the new project logo
- [x] Updated the `Guidelines` section
- - [x] Added the `General` subsection
- - [x] Added the `Licensing` subsection
- - [x] Added the `Performance` subsection
- [x] Updated the `Candidate systems` section
- [x] Added the `Common confusion` section
- [ ] ...
- - [x] Updated the `Logo` subsection
- - [x] Added the `Culination` subsection
- [x] Removed the file version stamp in place of a file info section
- [x] Added the `file info` section
- - [x] Added the version number
- - [x] Added the version date
- - [x] Added the line count
- [x] Added the `file history` section
- - [x] Added an entry for version 1
- - [x] Added an entry for version 2
- - [x] Added an entry for version 3
- [x] Added the footer 
- [ ] No other changes in version 3

</details>

<details><summary><p><b>Version 4 (2023, Saturday, February 18th at 3:14 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Added a description about the logo
- [x] Updated the `Reasoning` section
- [x] Updated the `Common confusion` section
- [x] Added the `Pros` section
- [x] Added the `Cons` section
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 4
- [ ] No other changes in version 4

</details>

</details>

***

###### Footer

You have reached the end of this page.

***
