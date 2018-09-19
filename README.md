# Lean Notes

This is a repository collecting all my thoughts on best practices and how-to guides for pursuing any sort of project or idea, whether it be a book, or a Web app, or a board game, or a 3D model, or a screenplay, or a microchip, or an essay, or a robot, or a logo, or whatever.

One of the things I struggle with is *organizing* these thoughts, so I've just dropped them into a big unordered bag called `content/`, and will describe the ways to browse through them below.

## Layout

### Content

All files under `content` are supposed to be accessible by links from this README (though most files are at least 1 link away).

Right now, all indexes into this content are in the content of the history section below.

### Tags

There are images under assets/tags that are linked to within content files, for use in "tagging" certain kinds of text.

There's a document giving attribution (but not explanation yet) for the designs that will be used going forward [here][Tag readme].

## History

This repository, in its current state, is a mix of a few different projects I've started in the past:

### The original Lean Notes series (first drafted on Trello)

I had a series of cards on a collection of Trello boards that I was using to mock up something : https://trello.com/leannotes

Back on January 18, I decided that, for accessibility's sake (and growing increasingly wary of Trello since its acquisition by Atlassian), I'd rather have these notes written as Markdown essays on GitHub (for easy replication to anywhere else Git is supported).

At the point in September 2018 when I merged these other projects below into this repo (and refactored it into files by UUID in the process)

But even when it came to the original boards on Trello, some chapters had little to no content beyond a title and a summary. Some Previous / Read On lists will lead off in directions that don't make any sense. Some sections may just link off to a GitHub Issue for details instead of having something written in the text itself (and *that* issue may have nothing in it).

See [issue #1](https://github.com/stuartpb/leannotes/issues/1) for more information on the process of migrating these to GitHub; file a new issue if there's something specific missing that you'd want to know, and I'll answer if I can.

Even when it was on Trello, I was experimenting with *multiple* Tables of Contents, sorting by different criteria:

- [The first one ("Table A")][Table A] is the general "order" you might want to go through if reading "cover to cover". It presents things in a somewhat interleaved fashion, explaining ecosystem between mechanics, things like that. It's well paced, but somewhat non-linear.
- [The second one ("Table B")][Table B] is sorted by scope. It's more "linear" and "focused", but more stratified: "learning" isn't as mixed with "doing". Table A links to all the content that was on boards in Lean Notes, but Table B doesn't have a place for all of them.

In the merged version of this repository, these Tables have been kept, and may be developed out to incorporate content from some of these other projects, or integrated into some larger "index documents " that may link to them as part of a larger-scope guide.

### The how-i-roll repository

This was another, similar project to Lean Notes, but with more of an eye toward describing my own *specific* procedures I follow when setting out to do things. It contained three significant files that have been merged in here:

- A file on using [GitHub Issues as Notes][]
- A file on [How Stuart P. Bentley Starts Projects][]
- A file on [how I write on GitHub][how-i-roll writing], which this merge has made significantly less relevant (this file should be revised soon).

### A bunch of other half-baked concepts I'd made repos for

Here are some loose pages I'd originally planned to write entire books (or at least booklets) for, most of which had been linked in my list of [Collected Writings][], often with more text being dedicated to describing *what the planned repository was intended to collect* than *actual text within the repository* (for many of these, those descriptions form the bulk of their content here):

- [stuartpb On Security][]
- [Nerd First][]
- [Undesign][]
- [Primer Prime][]
- [Everybody Gets a Factory][]
- [Namespace Taboos][]

## Roadmap

Going forward, I'm looking to go through this repository and start cross-referencing these sorts of sub-projects, breaking them out into separate documents in some places, and merging them together in others, until it's all a big ball of hair, with a few good points of entry that can help you see everything that can help you, in an order that makes sense.

[Collected Writings]: https://github.com/stuartpb/collected-writings

[Table A]: content/c8c4173e-e0ca-4218-a33a-e5b0ae48e9ef.md
[Table B]: content/ac01173b-4650-4609-aa84-0ded42714396.md
[GitHub Issues as Notes]: content/8c7b7b53-cbd4-487b-a8e7-e72d7e527982.md
[How Stuart P. Bentley Starts Projects]: content/e7d1004b-5a6f-44c4-a0ea-ab7815460638.md
[how-i-roll writing]: content/8801d68b-a815-4c92-b9af-503aa47b1848.md
[stuartpb On Security]: content/4dd64124-8e20-4901-aae4-5876361adc85.md
[Nerd First]: content/f63f28c0-aa23-44c0-b7b3-9b043489d132.md
[Undesign]: content/ff2268ae-d330-4eb4-847e-540718a0ceb6.md
[Primer Prime]: content/b4195691-701c-48c6-a3d7-e4fe9123728e.md
[Everybody Gets a Factory]: content/8cbd867d-1a63-4d1f-9c83-cab019fe87bd.md
[Namespace Taboos]: content/ec13f80e-f367-4dd9-b4c3-c9b27c136167.md

[Tag readme]: content/ced13582-8e1a-4b38-9469-896206590dfb.md
