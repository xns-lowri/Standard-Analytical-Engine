# Development of the Analytical Engine Industry, 1837-1908:
N.B.: The timeline described herein is fictionalised and does not represent historic fact. Please do not use this repo as a source for any historical research!

### 1837 - Babbage's Experimental Analytical Engine
Charles Babbage sets out the architecture of the Analytical Engine: a separate Store and Mill, decimal figure wheels, punched-card control, automatic sequencing, and general-purpose arithmetic. Early designs are extremely ambitious, using very wide native numbers and elaborate mechanical arithmetic.

### 1840s - Government Engine Programme
With sustained government funding, Babbage’s designs progress from experimental mechanisms into complete working machinery. A practical Difference Engine establishes confidence in automatic calculation and printing, while development of the Analytical Engine continues with increasing emphasis on reliability and manufacturability.

### 1848 - Royal Analytical Engine No. 1
The first substantially complete Analytical Engine enters service, principally for scientific, navigational, astronomical, and government computational work. It is enormous, expensive, and heavily engineered, but proves programmable mechanical computers as a practical technology.

### 1850s - Rise of the Engine Houses
Large Analytical Engines remain too costly for most private users, leading to centralised Engine Houses providing computation as a service. Government departments, observatories, insurers, engineers, and commercial firms submit card-work (usually data to be processed by a standard 'proven' pattern, sometimes complete patterns written by the customer) for processing and later receive printed results. Patterning (programming), card preparation, and Engine operation begin emerging as distinct professions.

### Mid 1850s - Telegraphic Working
Engine houses almost immediately begin accepting particulars and returning results by electric telegraph. Integration is initially entirely manual, with received telegrams transcribed into pattern selections and store settings by clerks.

### 1856 - Lovelace Card Standard
A standardised system for encoding instructions and data on two sets of punched cards develops from the earlier work of Babbage and Lovelace. Compatible card-work commodifies computing by allowing patterns to be exchanged between Engines, and encourages further development of reusable Pattern Libraries. The distinction between an Engine's physical construction and the patterns used to control it become increasingly important.

### Late 1850s-1860s - Industrial Application
Analytical machinery spreads beyond pure scientific calculations. Textile manufacturers use engines to calculate and prepare Jacquard patterns. Railways, insurers, banks, and manufacturers begin using engines for scheduling, accounting, statistics, and records processing.

### Late 1850s-1860s - Automatic Telegraphic Ingress
Experimental interfaces allow specially formatted telegraphic traffic to be recorded directly onto punched media suitable for Engine input. High-volume engine houses implement dedicated telegraph instruments allowing remote offices to send pre-prepared work requests, particulars, and even full patterns for processing. Results are returned when ready, with some branch offices employing sophisticated automatic printing apparatus for handling the reception, formatting, and printing of results sent from the engine house.

### 1862 - First Commercial Engines
Commercial makers challenge Babbage's enormous native word widths. A compact six-figure architecture demonstrates to a captivated audience at the London International Exhibition that an analytical engine the size of a large dining table could perform extended precision computation with reasonable performance by making heavy use of multiple store columns and additional workings to handle carry and borrow. Other exhibitors show off the latest developments in maintainability and modular design with standardised store and mill components and replaceable cage assemblies. Also notable was Thomas F. Wilkinson & Co. taking the show by storm when they unveiled their ground-breaking Graphical Patterning Unit, used to interactively produce pattern designs for their newest range of engine-controlled Jacquard looms.

### 1860s - Early Adoption
Standardised designs begin to replace individually fitted analytical engines as private enterprises increasingly adopt more affordable analytical engines for serving routine computational tasks in-house. 

### Late 1860s - Standard Eight-Figure Architecture Adopted
The emerging industry converges on eight-figure native words as a useful compromise between complexity and performance. Mechanical flags, conventionally described as HIGH or LOW according to their physical positions, become a standard control abstraction distinct from decimal figures. Standards establish common dimensions and interfaces for store and mill equipment, and expose arithmetic condition flag states to the running pattern for the first time, simplifying the implementation of extended precision operations. The design proves inexpensive enough to manufacture in quantity yet performant enough to be commercially viable.

TODO section to be updated following experiments and analysis of different architectures - column height (word width) might be too narrow if adding machines are anything to go by, but also 8 figure is equivalent to ~27bit so probably fine for general purpose computing given 8-bit micros rule the world and early computing research was mainly focused on mathematical computation.

### 1874 - Carriage Interface Standardised
Competing implementations are consolidated into a common convention for the generation, retention, testing, and consumption of carriage and borrow states. This permits patterns employing extended arithmetic to operate consistently across compatible Engines.

### 1870s - Native Decimal Control Techniques Mature
Engine designers increasingly seek to improve the branching performance of their products. Noticing the trend in using single figures as representations of enumerated states, one manufacturer is granted a patent for a  device called a 'branch comb'. This obscure device, which selects one of up to ten control paths directly from the position of a figure wheel, quickly becomes a characteristic feature of decimal engine architecture. 

### 1878 - Carwen ???
"the present"
Standard eight-figure analytical engine, the target development and kernel of educational value behind this silly alt history story.

TODO also: thread in the development of divided- and common-store designs, and instruction caching strategies.
