Evidence is the first step in planning.

## Introduction

What is evidence?

Evidence is anything you know or find out by observing the GoodNotes application.
It can be collected as screenshots, videos, or texts describing the observed behaviours.

We are collecting evidence in the Evidence folder. Evidence acts as the most basic useful tool for designing and adjusting GoodCraft and to ensure parity.

## Contributing Evidence

I want to help with evidence!

If you want to contribute evidence, all you need is access to a GoodNotes installation. You can take screenshots, screen recordings or document behaviour in text form.

Make sure that no personal information is shared without censor, as this is a **public GitHub repository**, and **anyone**, in other words **everyone** has permissions to look at it.

Before contributing evidence try to make sure it's not collected already! Duplication doesn't hurt until it only contributes more work.

## Categorizing Evidence

Evidence by itself is only really useful after it's categorised. Currently we're putting it into folders describing different parts of the app. We're creating subfolders if there is an area that requires special attention and needs a lot of explaining. The more explaining an area needs, the more complexity it possesses. It will take more time to implement. Our goal is to break up complexity until it becomes structured. That's why it's important to section the app up nicely.

Areas of the app determined so far:
- Browser
- Editor
- Market
- Notebook_Templates
- Onboarding
- OS
- Settings
- Tour
- Unsorted

## Completeness

Evidence collected from the start is likely **incomplete**. This is because during the process of implementation questions will arise: What happens if I scroll down, or do this specific combination of interactions? These unknowns are often hidden from the start: You will only realise them once you start implementing a specific functionality.

## Describing Evidence

After the evidence has been categorised we need to start doing the work to transform it into text. This is a lot of effort and contributions are very welcome. More information on this process will follow.

LLMs still work the best with text descriptions, which they translate into code. They can only "see" what we describe to them. This is why providing an extremely detailed and accurate description is important.

Descriptions can be modular. Luckily we are working with software, so optimally we don't want to describe everything repeatedly. Describe things exactly once, give them a name, and then refer to them every time they appear again. We can always pull up the description and also it helps encouraging the same modularity within the code from the start.