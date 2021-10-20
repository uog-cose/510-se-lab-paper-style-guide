# House Rules for Writing Papers in the 510 Lab

These are some guidelines for writing papers developed with the 510 Lab, written in the style of the [Rules of the Velominati](https://www.velominati.com/). Please submit merge requests!

## Authors

Tim Storer

# Learning the Rules



# The rules

## The Audience

1. Treat the readers and reviewers like idiots.  You can't blame an idiot for not interpreting what you write in a predictable way.  That's just the nature of idiots.    If they do this, then the fault is your own for not accommodating their idiocy.  Try again, explaining more clearly.
2. Imagine that you are explaining a task to your children.  If you don't have children, imagine you are explaining to someone else's.  Unless you explain every detail completely clearly you will eventually have to do it yourself.
3. Avoid introducing concepts that don't support the central focus of your work.

## Don't Pick a Fight with LateX

1. LaTeX code should be hard wrapped at 120 characters. This enables readers of the source code to parse each line without losing vertical position in the text.  Hard wrapping also helps to minimise diffs (see next rule.)

2. LaTeX source code should be change managed (choose a VCS that your co-authors also use).  Compiled or generated files should not be included in the change management code.

3. Let the layout engines in tools like LaTeX work for you.  Avoid using placement specifiers like [h]. A figure should be inserted immediately after its first reference in the main body of text. Let LaTeX do the rest.

   

## Clarity

1. Spelling mistakes, even auto-corrected spelling mistakes are not to be forgiven.  Equally, native English speakers should be a whole lot more sympathetic to non-native English speakers.  Ask them to try writing their PhD thesis in Arabic.
2. Terminology should be used consistently.  For example, I don't refer to both 'ideas' and 'concepts' in the previous paragraph.  To do so would be to imply that they are different, which confuses the reader.  Think about telling you child to put on their coat.  Telling them to find their jacket and then put on their anorak will confuse them. Keep it simple and clear.
3. All figures should be fully explained (see The Audience, Rule 1) rather than left to interpretation by the reader.  A paper is a user manual, not a work of modern art.  A figure should not be used as a substitute for a paragraph of text.
4. Look for repetition of text as opportunities to be more concise.  Simple examples are repetition of words in the same sentence, or the repetition of a prefix phrase in a list of items. 
5. Look for phrases that indicate duplication "Moreover", "In other words".  Why say something twice? Just pick the best explanation and improve it.

## Specificity

1. Check that *every* sentence makes a specific point relevant to your document.  A good test of the usefulness of a sentence is to ask yourself if the sentence could be included in any paper.  For example, the first sentence of a literature review chapter that reads "This chapter presents a review of the relevant literature." is not useful.  It doesn't tell me that the relevant literature is for the topic at hand.

## Structure

1. Work out how to break your narrative down into paragraphs that are between three and seven sentences long.  This prevents the narrative within a paragraph from being too broken, allows an idea to be developed within a paragraph, but prevents the paragraph from being so long that the single idea is too complex for a reader to hold in their mind.

2. The first sentence of a paragraph should make clear the paragraph purpose.  The intermediate sentences should elaborate on and develop the single idea of the paragraph and not be distracted by other ideas.  The final sentence should conclude the idea contained within the paragraph.

3. The first paragraph should be as narrowly focused on the topic of the whole paper as possible.  Introductions that begin "Computing technologies have revolutionised society" when the topic of the paper concerns a novel algorithm for traffic management in a network wastes space before getting to the relevant bit.  Focus on what the narrow context is for your innovation.

4. Each paragraph should build incrementally on the previous paragraph.

5. Avoid forward references.  The only exception to this is the structure section of the introduction.  See next rule (that's a joke, by the way).

6. All papers follow the same structure: introduction, related work, design, results, conclusions.  Variations to this include insertion of a 'discussion' between results and conclusions; or moving related work after results.  This is done to allow comparison between prior results and the new results.
7. All introductions follow the same pattern: background; motivation; research questions; contribution; structure.

8. All conclusions follow the same pattern: summary, discussion, limitations, future work and generalisable lessons. Conclusions should *conclude* a paper, not just summarise them.  Answer the questions: what have we learned? what can we generalise from this?
9. A paper should be divided into two or more roughly equal sections. A section should be broken down into two or more roughly equal sub-sections, and so on.  A corollary of this is that you should never have an single section by itself at any depth. I call these dangling sub-sections because of how they appear in the table of contents, but you can think of them as 'only-child' sub-sections.  A dangling sub-section can either be merged with its parent or promoted to be a section in its own right.



## References

1. References should be consistently formatted.  Bibtex and other tools will get you a long way on this, but you still need to take care of the source formatting.  A good shortcut is to use the DBLP version of a reference wherever possible.

2. Be aware of the difference between an inline textual citation, such as Storer's [2021] style rules and citations given in parentheses [Storer, 2021].  Never, ever, use a citation in parentheses as though it should be read as an inline textual citation.  Assume that anything in brackets should only be optionally read by the reader. 

   > "It was really annoying that [Storer, 2021] banged on about the spelling"

   should be read as:

   > "It was really annoying that banged on about the spelling".

   This is particularly important when numbered references rather than Harvard style is used.
