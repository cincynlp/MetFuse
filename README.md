# MetFuse
Dataset for the ACL 2026 paper: "MetFuse: Figurative Fusion Using Metonymy and Metaphor"

**What is MetFuse?**
MetFuse is the first dataset to combine instances of metaphor and metonymy together, creating hybrid instances. The dataset has been annotated by humans and contains 1,000 quadruplets of literal sentences, and its corresponding metonymic, metaphoric and hybrid variation. 

Each instance includes:
• A literal sentence
• The target **noun**
• The target **verb**
• The **metonymic variation** of the literal sentence.
• The **metonymic paraphrase** (altered noun) that creates the metonymy.
• The **metaphoric variation** of the literal sentence (the verb has been altered).
• The **hybrid variation** (combining the altered noun and the altered verb), combining metaphot and metonymy.
• The category of metonymy (NE: Named-entity metonymy, or CN: common noun metonymy)

Example:
Target Word: lawyer
Verb: see
MetPar: law office
Sentence: the **lawyer** in lincoln **saw** issues.
Metonymy: the **law office** in lincoln saw issues.
Metaphor: The lawyer in Lincoln **beheld the behemoth** of issues.
Hybrid: the **law office** in Lincoln **beheld the behemoth** of issues.
Category: CN (common noun)
