# Physical vs digital premise

*Parataxis* is the advantage of the physical system.
For retrieval, digital is far superior via `rg`, `fd`, and `fzf`.
But is it also better creatively?


## Physical Zettelkasten experiment findings
Experimenting with physical Zettelkasten.
Fragments are fruitful.
Great for creativity.
Counters problems of writing style.
Writing note body is low friction.
But writing meta boilerplate is high friction.
Yet no mobility in a Zettelkasten without an index.
Indexing is tough.
Previous values can't be overwritten.
Indexing is very instructive and a good practice because of this.
Good to continue.

### Use for business
Indexed Zettelkasten useful in a business context *if and only if* it's centralized.
The box is useless if you're not in your office.
You can write but not retrieve cards when away.
Amnesic idiot-nomad.
And a portable Zettelkasten sucks.
*The Zettelkasten directs the behavior in the office.*
You need a centralized box.
But centralized better if distributed.
Since copying 3x5 index cards by hand is ridiculous, printing `git` revisions of Zettelkasten onto physical cards is superior.
These cards can be stylized.
Solve printing et voilà.

Digital Zettelkasten is a better permanent format.
Revisions, cloud, centralized, easily distributed, and VCS.
Yet it is less visible. 
This is a problem in a business context.
Therefore the perfection of the digital ZK by printing on to portable cards above.
Metadata would be handled automatically and according to a regular schema.
Interior mobility of the cards is not a problem, as the index can be "nullified" or "softened" prior to printing.
The tree is refined from the leaves first, much like evolution naturally selects *in a habitat*.
Enclaves are first populated, and then *defined*.
Zettelkasten can't be on a desk but on a computer with a battery.
Resists time, unlike the physical Zettelkasten.
Now to define a digital Zettelkasten.
But first, the essence of *any* Zettelkasten.

## Essence of Zettelkasten
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

# Key concepts
1. Zettelkasten as a naturally selected knowledge tree; redefinition of the information habitat -- neighbors of the information, neighbors of the notes. Symbiosis of certain species the only means of survival.
