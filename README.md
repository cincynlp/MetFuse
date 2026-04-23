# MetFuse (Metaphor-Metonymy Fusion Corpus)
Dataset for the ACL 2026 paper: "MetFuse: Figurative Fusion Using Metonymy and Metaphor"

**What is MetFuse?**<br>
MetFuse is the first dataset to combine instances of metaphor and metonymy together, creating hybrid instances. The dataset has been annotated by humans and contains 1,000 quadruplets of literal sentences, and its corresponding metonymic, metaphoric and hybrid variation.<br>

Each instance includes:<br>
• A literal sentence<br>
• The target **noun**<br>
• The target **verb**<br>
• The **metonymic variation** of the literal sentence.<br>
• The **metonymic paraphrase** (altered noun) that creates the metonymy.<br>
• The **metaphoric variation** of the literal sentence (the verb has been altered).<br>
• The **hybrid variation** (combining the altered noun and the altered verb), combining metaphot and metonymy.<br>
• The category of metonymy (NE: Named-entity metonymy, or CN: common noun metonymy)<br>

Example:<br>
Target Word: lawyer<br>
Verb: see<br>
MetPar: law office<br>
Sentence: the **lawyer** in lincoln **saw** issues.<br>
Metonymy: the **law office** in lincoln saw issues.<br>
Metaphor: The lawyer in Lincoln **beheld the behemoth** of issues.<br>
Hybrid: the **law office** in Lincoln **beheld the behemoth** of issues.<br>
Category: CN (common noun)<br>
