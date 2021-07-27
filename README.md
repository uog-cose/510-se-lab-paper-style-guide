# House Rules for Writing Papers in the 510 Lab

These are some guidelines for writing papers developed with the 510 Lab, written in the style of the [Rules of the Velominati](https://www.velominati.com/). Please submit merge requests!

## Authors

Tim Storer

## The rules

Any given passage should be written with the mindset that you are explaining a task to your children.  Unless you explain every detail completely clearly you will eventually have to do it yourself.

Spelling mistakes, even auto-corrected spelling mistakes are not to be forgiven.  Equally, native English speakers should be a whole lot more sympathetic to non-native English speakers.  Ask them to try writing their PhD thesis in Arabic.

Work out how to break your narrative down into paragraphs that are between three and seven sentences long.  This prevents the narrative within a paragraph from being too broken, allows an idea to be developed within a paragraph, but prevents the paragraph from being so long that the single idea is too complex for a reader to hold in their mind.

The first sentence of a paragraph should make clear the paragraph purpose.  The intermediate sentences should elaborate on and develop the single idea of the paragraph and not be distracted by other ideas.  The final sentence should conclude the idea contained within the paragraph.

Terminology should be used consistently.  For example, I don't refer to both 'ideas' and 'concepts' in the previous paragraph.  To do so would be to imply that they are different, which confuses the reader.  Think about telling you child to put on their coat.  Telling them to find their jacket and then put on their anorak will confuse them. Keep it simple and clear.

The first paragraph should be as narrowly focused on the topic of the whole paper as possible.  Introductions that begin "Computing technologies have revolutionised society" when the topic of the paper concerns a novel algorithm for traffic management in a network wastes space before getting to the relevant bit.  Focus on what the narrow context is for your innovation.

Each paragraph should build on the previous paragraph.

Avoid forward references.  The only exception to this is the structure section of the introduction.  See next rule (that's a joke, by the way).

All introductions follow the same pattern: background; motivation; research questions; contribution; structure.

All papers follow the same structure: introduction, related work, design, results, conclusions.  Variations to this include insertion of a 'discussion' between results and conclusions; or moving related work after results.  This is done to allow comparison between prior results and the new results.

Let the layout engines in tools like LaTeX work for you.  Avoid using placement specifiers like [h]. A figure should be inserted immediately after its first reference in the main body of text. Let LaTeX do the rest.

All figures should be fully explained (see Rule 1) rather than left to interpretation by the reader.  A paper is a user manual, not a work of modern art.  A figure should not be used as a substitute for a paragraph of text.

Conclusions should conclude a paper, not just summarise them.  Answer the questions: what have we learned? what can we generalise from this?

A paper should be divided into two or more roughly equal sections. A section should be broken down into two or more roughly equal sub-sections, and so on.  A corollary of this is that you should never have an single section by itself at any depth. I call these dangling sub-sections because of how they appear in the table of contents, but you can think of them as 'only-child' sub-sections.  A dangling sub-section can either be merged with its parent or promoted to be a section in its own right.

Look for repetition of text as opportunities to be more concise.  Simple examples are repetition of words in the same sentence, or the repetition of a prefix phrase in a list of items. 

## References

References should be consistently formatted.  Bibtex and other tools will get you a long way on this, but you still need to take care of the source formatting.  A good shortcut is to use the DBLP version of a reference wherever possible.

Be aware of the difference between an inline textual citation, such as Storer's [2021] style rules and citations given in parentheses [Storer, 2021].  Never, ever, use a citation in parentheses as though it should be read as an inline textual citation.  Assume that anything in brackets should only be optionally read by the reader. 

> "[Storer, 2021] banged on about the spelling"

could be read as:

> "banged on about the spelling".

This is particularly important when numbered references rather than Harvard style is used.
