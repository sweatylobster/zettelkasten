# Physical vs digital premise

*Parataxis* is the advantage of the physical system.
For retrieval, digital is far superior via `rg`, `fd`, and `fzf`.
But is it also better creatively?


## Physical Zettelkasten experiment findings
Experimenting with physical Zettelkasten.
Great for creativity.
Note body is low friction.
Fragments fruitful.
Counters problems of writing style.
But writing meta boilerplate is high friction.
Yet no mobility in a Zettelkasten without an index.
Stamp datetimes, don't write them.
Indexing is tough.
Previous values can't be overwritten.
Indexing is very instructive and a good practice because of this.
Good to continue.

Indexed Zettelkasten useful in a business context *iff* it's centralized.
The box is useless if you're not in your office.
You can write but not retrieve cards when away.
Amnesic idiot-nomad.
And a portable Zettelkasten sucks.
Clunky, and unreliable in a business context.
*The Zettelkasten directs the behavior in the office.*
You need a centralized box.
But centralized better if distributed.
Since copying 3x5 index cards by hand is ridiculous, printing `git` revisions of Zettelkasten onto physical cards is superior.
These can be stylized.
Digital Zettelkasten more applicable to business.
Solve printing et voilà.
Now to define a digital Zettelkasten.

## Essence of Zettelkasten
But first, the essence of any Zettelkasten.
*Zettel* -- note,
*Kasten* -- crate/box.
Note-box.
We need to add, store, and review slips.
That's it.
Minimize friction of adding *ein Zettel*.
1. Write fragments and not essays. Enforce short bodies. The interior mobility is the priority. (Notable difference from Mischa van den Burg's use of the technical Markdown Zettelkasten.)
2. Compose fragments to make essays. (Inspired by Roland Barthes's manner of writing.)
An index is not only a UUID -- *it is a tree that groups by intuition*.
Digital version is wanting in a spatial *parataxis* tool.
Yet it might excel in regrouping.

## Digital Zettelkasten design
Goal is an optimal schema for a *business* Zettelkasten.
Notes must be compressed and informative.
Digital notes should be practically equivalent to index cards.
I should feel like I'm leafing through the Zettelkasten with `fzf --preview 'bat -p -f {}'`.
Automate meta tags and enforce short bodies.
Once again, note the difference from Mischa van den Burg's Zettelkasten.

Metadata inscription must be automated and easy to overwrite.
While indices intuitively group, we have digital directories.
Examine hierarchies with `tree` or `eza --tree`.
`oil.nvim`, `nnn`, and `fx` enable digital *parataxis*.
Files can belong to a single directory and be arbitrarily sorted.
But the thinking must always be easy to represent as a graph.
Store sort orders in `config.yaml` files.
Re-mobilize the Zettelkasten as you please by tags and other content headers.
Big thought is to connect it to an LLM that can inherit conceptual trees.

```json
{
  "prompt": "Read the notes on questioning. Assign them to *business* or *philosophy*.",
  "notes": []
}
```

We desire graphs, especially *Directed Acyclic Graphs*; a *DAG* shows order of operations.
Create a tool to specify linkages (dependencies, ancestors, descendants) in a keypress.

Make file names regular.
Make them accessible like filepaths.
Allow them to be found with tree-like thinking.
Do not require crawling -- expose them via an easily-accessible tool.

## Hybrid digital to physical Zettelkasten for business
*The Zettelkasten directs the behavior in the office.*
A centralized paper Zettelkasten is indispensable with paper documents. 
The goal is automated paper hypertext.

## Costs of physical

Remove cognitive effort of indexing.
Reduce penstrokes to keypresses.
Use neovim to organize and index.
