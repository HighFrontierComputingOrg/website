# ***DECWAR: How a University Mainframe Became a Multiplayer Galaxy***

# Prospectus

## Brief Description

*DECWAR: How a University Mainframe Became a Multiplayer Galaxy* tells the history of a text-only multiplayer game created on the University of Texas at Austin’s PDP-10 in 1978\. As many as eighteen players at separate terminals could inhabit one shared galaxy, commanding starships, capturing planets, building bases, fighting opponents, and communicating by radio through typed commands. The game circulated among universities as source code before reaching CompuServe, where it became the long-running commercial game MegaWars. By following DECWAR from its roots in *Star Trek*\-inspired BASIC text games through its university development, commercial transformation, near disappearance, and recovery, the book reveals an overlooked path to online worlds—one shaped by common text-only terminals,  institutional mainframes, pop culture, shared and often locally customized software, and early commercial online services rather than arcades, consoles, or game studios.

The book combines archival research and interviews with creators, maintainers, and players with close analysis of more than 20,000 lines of surviving FORTRAN and MACRO-10 code. Restoring and running historical versions, producing a precise game specification, and building a modern implementation allow the authors to test memories, documentation, technical claims, and differences among versions. Technical ideas such as separate jobs, shared memory, terminal speed, and command processing will be introduced through their consequences for players and programmers. Scenes of play, terminal sessions, diagrams, annotated source excerpts, and version comparisons will make the evidence accessible to readers without programming or mainframe experience while showing how reconstruction can serve as a method of historical inquiry.

## Outstanding Features

1. A distinct account in the history of online multiplayer games, from university computing to early commercial online services.  
     
2. A close explanation of DECWAR’s central technical innovation—using a PDP-10’s job system to allow as many as eighteen players to command separate starships within a single shared galaxy.  
     
3. A full explanation of how DECWAR operated as a game, including its commands, rules, objectives, interconnected systems, strategies, and distinctive idiosyncrasies.  
     
4. An examination of how the computing environment became part of DECWAR’s game design: separate TOPS-10 jobs and round-robin-style scheduling enabled simultaneous play, while shared memory and differing baud rates shaped the game’s rhythm, balance, and experience.  
     
5. A lively exploration of the surprising connections among BASIC, *Star Trek* fandom, text-based space games, university computing culture, time-sharing, computer networking, commercial online services, and the emergence of multiplayer worlds  
     
6. A vivid history brought to life through interviews, oral histories, and the personal recollections of those who created and played DECWAR and MegaWars.  
     
7. A treatment of source code as historical evidence. The book analyzes more than 20,000 lines of FORTRAN and MACRO-10 assembly, using AI-assisted methods to recover the game's syntax, semantics, and behavior.  
     
8. A combination of historical research and executable reconstruction. A precise game specification and modern implementation make it possible to test interpretations, compare versions, and distinguish DECWAR’s original design from later changes.  
     
9. An investigation of why a world created entirely through text could be so compelling during the rise of graphical video games—and why its shared galaxy inspired players across both university and commercial settings.  
     
10. A playable companion to the historical account. A running version held by the University of Texas at Austin will be made publicly available alongside the book, allowing readers to experience the game and potentially helping a new community of players form around it.  
      
11. An accessible presentation of technically complex material through player actions, terminal sessions, diagrams, annotated code, and reconstruction stories, requiring no background in programming or vintage computing.  
      
12. Firsthand accounts from key figures including DECWAR co-creator and programmer Bob Hysick, and Bill Louden, who oversaw MegaWars at CompuServe. Their recollections, along with those of other contributors and players, add depth and interest to the book.

## 

Competition

DECWAR receives brief coverage in several histories of games and online computing, but we have not identified a sustained, independently researched account of the game. The closest comparisons include histories of individual games, studies of early multiplayer worlds, and books that explain software through its design and source code. The discussion below compares their subjects, approaches, and depth with those of the proposed book.

*Research note: AI-assisted tools were used to identify relevant titles, locate supporting sources, and help organize and draft the comparative analysis below. Many of these works were already familiar to the authors.*

# Closest comparisons

| Work | Strengths and approach | Comparison with *DECWAR* |
| :---- | :---- | :---- |
| Chaim Gingold, *Building SimCity: How to Put the World in a Machine* (MIT Press, 2024\) | Combines a detailed history of *SimCity* with an explanation of how its simulation works. Its diagrams make complex systems understandable, while its historical narrative connects the game to earlier ideas about computing, modeling, and design. | A close comparison in structure and intended readership. Both books explain a game’s operation and place it in a wider history. Gingold’s subject is urban simulation; *DECWAR* examines text-based space combat and an early shared multiplayer world. Its technical chapters will similarly connect implementation to recognizable events in play. |
| Sarah Ciston et al., *Inventing ELIZA: How the First Chatbot Shaped the Future of AI* (MIT Press, 2026\) | Reconstructs ELIZA’s development through archival research and close readings of recovered code and related documents. A working recreation accompanies the historical account. | Particularly relevant to “The Language of the Game,” “Recovering DECWAR,” and “Porting the Game.” Both books use recovered code and working software to investigate historical questions. ELIZA concerns conversation with a computer; DECWAR examines how people played together within a shared world. |
| Brian Dear, *The Friendly Orange Glow* (Pantheon, 2017; Vintage, 2018\) | An expansive, interview-rich history of PLATO that makes university computing and early online life accessible through the people who built and used the system. Its coverage of multiplayer games makes it especially relevant. | Dear follows a computing system and its many applications and communities. DECWAR follows one game, connecting its university setting, development, and player culture with its later commercial life. The books share an interest in the people and social experiences behind early online computing. |
| Richard A. Bartle, *Designing Virtual Worlds* (2003; second edition, Volume I, 2026\) | A detailed account of virtual-world design informed by Bartle’s experience as a creator of MUD. It combines historical knowledge with practical discussion of how online worlds operate. | Shares important concerns with DECWAR’s rules, simultaneous activity, and shared space. Bartle’s purpose is to explain virtual-world design across many examples. *DECWAR* is a historical account of one game, including the specific code and computing environment that made its design possible. |
| Aaron A. Reed, *50 Years of Text Games* (Changeful Tales Press, 2023\) | An illustrated history of text games, with one game representing each year across five decades. Reed explains how the games worked, who created them, and the settings in which they emerged. | Reed surveys many games; our book examines one in depth. DECWAR appears briefly in his discussion of Trade Wars. We expand on that history through interviews, archival research, and analysis of the game’s design, software, and adaptation into MegaWars. |
| Raiford Guins, *King PONG: How Atari Bounced Across Markets to Make Millions* (MIT Press, 2026\) | A focused history of *PONG* that explains its success through Atari’s business decisions and movement between markets. It demonstrates how much history can be found in a seemingly simple game. | A useful comparison for the transition from DECWAR to MegaWars. *PONG* began as a commercial product; DECWAR began in university computing and entered the commercial market later. DECWAR pairs that commercial history with a closer look at the game’s language, rules, and architecture. |
| Nick Montfort, *Twisty Little Passages: An Approach to Interactive Fiction* (MIT Press, 2003\) | Combines a history of interactive fiction with an examination of how it works as both literature and a game. It offers a substantial account of text as a medium for interaction. | A close comparison for DECWAR’s textual interface and command language. Montfort’s emphasis is interactive fiction, particularly narrative and puzzles. *DECWAR* examines commands used for tactical action in a world changing through simultaneous play, including a formal account of how those commands are interpreted and executed. |

# Adjacent comparisons

| Work | Strengths and approach | Comparison with *DECWAR* |
| :---- | :---- | :---- |
| Melanie Swalwell, *Homebrew Gaming and the Beginnings of Vernacular Digitality* (MIT Press, 2021\) | Uses interviews and archival research to recover the work of homebrew game creators in Australia and New Zealand. It takes everyday programming and experimentation seriously as game history. | Closely related to DECWAR’s beginnings outside the commercial game industry. The principal difference is setting: Swalwell studies domestic microcomputers and their users, while DECWAR grew from access to institutional machines and circulated among computing centers. |
| Kevin Driscoll, *The Modem World: A Prehistory of Social Media* (Yale University Press, 2022\) | Explains the history of dial-up bulletin-board systems through their technology, local communities, and operating practices. It gives a clear account of online life outside the familiar history of the internet. | Relevant to remote access and the setting in which MegaWars reached paying customers. Its central subject is communication through bulletin boards. In DECWAR, communication accompanied simultaneous action inside a game, requiring a different account of both the software and its use. |
| Nick Montfort and Ian Bogost, *Racing the Beam: The Atari Video Computer System* (MIT Press, 2009\) | Explains how the Atari VCS shaped the design of six games. Technical detail is connected directly to gameplay, interfaces, and visual expression. | The clearest comparison for “The Machine in the Game.” *DECWAR* takes a similar interest in the relationship between platform and design, but examines a shared institutional computer. Operating-system jobs, shared memory, and terminal speeds matter here in ways they do not for a cartridge-based home console. |
| Nick Montfort et al., *10 PRINT CHR$(205.5+RND(1)); : GOTO 10* (MIT Press, 2012\) | Uses a single BASIC program to explore programming practice and computer culture. It shows how close attention to code can support a much larger historical discussion. | Relevant to DECWAR’s treatment of source code as evidence. The difference is in the object and purpose of the analysis: *DECWAR* explains the behavior of a complete, changing multiplayer game, including its command syntax, rules, timing, and interactions between players’ actions. |
| Katie Salen and Eric Zimmerman, *Rules of Play: Game Design Fundamentals* (MIT Press, 2003\) | Provides a vocabulary for examining games as systems of rules, forms of play, and cultural works. Its examples range across digital and nondigital games. | Relevant to the explanations of DECWAR’s design and its comparison with other game forms. It is a broad theoretical and instructional work, not a historical case study. *DECWAR* will examine how such design questions were answered in one particular game and implemented in its software. |
| Jesper Juul, *Half-Real: Video Games between Real Rules and Fictional Worlds* (MIT Press, 2005\) | Examines the relationship between a game’s rules and its fictional world, and the continuities between traditional games and video games. It connects theoretical questions to concrete examples. | Relevant to “Playing DECWAR” and “DECWAR in Game History,” particularly the relationship between computational rules and an imagined galaxy. Juul develops an argument across many games. DECWAR examines these questions through one game’s design, history, and player experience. |
| Jon Peterson, *Playing at the World*, second edition (MIT Press, 2024–25) | A deeply researched history of role-playing games and their roots in wargaming, fantasy, and hobbyist communities. Its attention to the development of rules makes it relevant beyond the history of *Dungeons & Dragons*. | An important comparison for “DECWAR in Game History,” especially its treatment of combat, strategy, and game conventions. Peterson’s subject is primarily tabletop gaming. *DECWAR* examines what happens when rules are executed by a computer and multiple participants act within the same changing space. |
| Henry Lowood and Raiford Guins, eds., *Debugging Game History: A Critical Lexicon* (MIT Press, 2016\) | Examines the histories and meanings of concepts used to discuss games, including simulation, code, mechanics, and world-building. Its essays encourage historical analysis beyond a sequence of releases and technical milestones. | Provides useful comparisons for the book’s historical study of DECWAR’s design. Its organization is by concept, with different authors and examples. *DECWAR* follows a continuous history, using one game to examine several of these questions together. |
| Raiford Guins, *Game After: A Cultural Study of Video Game Afterlife* (MIT Press, 2014\) | Examines what becomes of games and gaming hardware after their original use, including their lives in collections, archives, and preservation projects. | Closely related to “Recovering DECWAR” and “Porting the Game.” Guins studies preservation across different objects and settings. *DECWAR* follows the practical and interpretive problems of recovering one game, separating its surviving versions, and reproducing its behavior through emulation and modern software. |
| Steven Levy, *Hackers: Heroes of the Computer Revolution* (1984) | A vivid, character-driven history of programming culture, moving from institutional computers to personal computing and commercial games. It remains a useful comparison for writing about technical people and their work. | The overlap is strongest in “Computing in 1978” and “From WAR to DECWAR,” with their accounts of university programming culture and experimentation. Levy follows a wider movement through selected people and institutions. DECWAR follows the people who created, played, adapted, and preserved one game. |
| Steven L. Kent, *The Ultimate History of Video Games*, Volume 1 (2001) | A broad, interview-based account of the video-game industry, written for general readers. Its strength is the story of the companies, products, and personalities that shaped commercial gaming. | Useful for the surrounding history of arcade and home video games. Its industry emphasis leaves less room for institutionally supported games distributed outside ordinary retail channels. *DECWAR* addresses that setting through a focused account rather than attempting another general history. |

# Existing coverage of DECWAR

| Work | Contribution | Comparison with the proposed book |
| :---- | :---- | :---- |
| Jeannie Novak, *Game Development Essentials: An Introduction*, third edition (Cengage, 2011/12) | Includes a short first-person account by Bill Louden of obtaining DECWAR and adapting it into MegaWars. It is a valuable participant’s account of the commercial transition. | The passage is a recollection within a general textbook, rather than an investigation of the game’s history. The proposed book will develop this account through further interviews and comparisons of the surviving code and documentation, including changes to the game beyond its names and presentation. |
| Jimmy Maher, “Games on the Net Before the Web, Part 1: Strategy and Simulation” (2017) | A substantial online account placing DECWAR and MegaWars within the early commercial online services. It is particularly useful on CompuServe, connection costs, and the appeal of multiplayer games to subscribers. | Its subject extends beyond DECWAR and its direct adaptation to MegaWars. The proposed book will give the university game, its development, and its mechanics fuller treatment, supported by source analysis and reconstruction. The article is an important existing account, but not a substitute for that longer history. |
| *Decwar (Multiplayer Computer Game)*, attributed to editors Frederic P. Miller *et al.* | A 72-page volume bearing the game’s name. Initial research indicates that it consists largely of republished Wikipedia material.  |  |

## Apparatus

The book will include examples of gameplay, excerpts from interviews with DECWAR’s creators and players, a bibliography, and references. It will draw on a substantial visual archive that includes game screenshots and period photographs of machines, people, and facilities. Rights and reproduction permissions must still be researched and secured for some historical photographs, so the final selection will depend partly on clearance and availability. Much of this material will also be donated to the Dolph Briscoe Center for American History at the University of Texas at Austin, which is already preserving artifacts related to DECWAR.

Supplementary material will be provided online through a companion site. It will provide access to the historical implementation running under PDP-10 emulation, a new implementation built with modern technology, and a directly playable version of DECWAR, together with public source-control repositories and reproducible build documentation for all released code. As permissions allow, it will also include historical source materials, extended interview excerpts, a version timeline, supplementary figures, and teaching materials. Readers will not need the site or external software to understand the book.

## Audience

The book is written for general readers interested in the history of games, computing, technology, and online culture, including the communities that formed around early online games. It will also appeal to game designers and developers interested in how these games were constructed and the technical challenges their creators faced. It may also interest historians of computing and those involved in software preservation. Readers interested in Texas history and the history of the University of Texas at Austin will discover a little-known part of the university’s computing history.

Its academic audiences span game studies, media studies, history of computing, software studies, internet and network history, science and technology studies, computer science, digital humanities, and archival preservation. The book could be assigned in undergraduate and graduate courses in these fields, either as a complete case study or through individual chapters on game design, university computing, online communities, commercialization, and software reconstruction.

No programming experience, technical background, or familiarity with *Star Trek* is required. A few sections examine the software and system architecture in greater detail. Readers with a background in software development or information technology may appreciate these sections more fully, but others can skim the technical specifics without losing the narrative or historical argument.

## Authors

**Eric Freeman** first encountered DECWAR in the mid-1980s, when he observed the enthusiastic player culture surrounding the game in a university data center. At the University of Texas at Austin—the birthplace of DECWAR—he recalled the game while looking for a text-only programming exercise for his students. The search led him to create Decwar.org in partnership with Noah Smith in an effort to understand and preserve the original game, and make it accessible through modern technology. Freeman is a computer scientist (PhD, Yale University) with a particular interest in software architecture and a lifelong enthusiasm for Star Trek, placing DECWAR at an unusual intersection of his personal and professional interests. He is also an established author with eight books in print, including the perennial twenty-plus-year bestseller *Head First Design Patterns*, winner of a Dr. Dobb’s Jolt Award for technical excellence. He also serves as co-advisor for O’Reilly Media’s Head First book series.

**Noah Smith** first encountered DECWAR in 1984 and 1985 as a high-school student taking summer courses at Southwest Texas State University. There he experienced DECWAR as a thriving social phenomenon, with a roomful of players gathered at DEC-10 terminals for fiercely competitive matches. The game and the academic computing culture surrounding it helped inspire his path toward aerospace engineering. He continued following DECWAR through Usenet and the PDP-10 community, then returned to hands-on work with the game in 2024, building and running it under PDP-10 emulation. He subsequently reconstructed the original University of Texas source distribution, created a reproducible container-based environment, and developed automated players and a modern graphical interface—work that became part of Decwar.org in partnership with Eric Freeman. Smith is a professional data scientist and aerospace engineer (PhD, University of Texas at Austin) whose career centers on computational modeling, simulation, and optimization. He also brings a sustained commitment to the history of Texas computing, including archival research and oral-history interviews with DECWAR’s creators, maintainers, and players.

**Michael Baker** brings to DECWAR the perspective of a game developer, technical artist, and educator whose career has focused on how interactive systems become compelling experiences. Before joining the University of Texas at Austin, he spent two decades in games and visual-effects production, working on independent games and licensed projects based on Star Wars and Alien, developing tools for the open-source Bullet Physics Framework, and co-founding the Austin game studio Codex Worlds. He joined UT Austin in 2017 and now chairs the Department of Arts and Entertainment Technologies, where he teaches game design and technical art. His work emphasizes discovering game systems through play and exploring the possibilities of real-time technology, mixed reality, and immersive storytelling. In 2023, he founded the department’s Lab for Immersive Media. DECWAR brings these interests into historical focus: how the constraints of a PDP-10, text terminals, and a time-sharing environment became part of the mechanics and social experience of a shared galaxy. Baker’s combination of game-industry experience, game-design pedagogy, and institutional leadership makes him well suited to explain DECWAR as both an important artifact of UT Austin’s history and a still-compelling work of interactive design. He holds an MFA from the Imaging and Digital Art program at the University of Maryland Baltimore County.

## Market Considerations

Readers do not need an existing interest in DECWAR to be drawn to its story: how a university mainframe became home to a compelling multiplayer galaxy, and how a game created in Austin found a new life on a commercial online service.

The book offers what brief accounts of DECWAR cannot: a detailed history of its creation, the experiences of those who created and played it, and an explanation of how it worked. Interviews and surviving software provide evidence for examining questions that existing accounts leave unanswered. Readers can also play the historical and modern versions released alongside the book, connecting what they read to their own experience of the game.

Sales figures for comparable books are not publicly available, which makes the market difficult to judge. Based on our publishing experience, we tentatively estimate sales of 5,000–8,000 copies during the book’s first several years, with the possibility of reaching 10,000 through wider coverage of the book and playable game. We offer these as informed guesses rather than forecasts, and we would refine them with the publisher using comparable book sales.

Relevant professional organizations and established communities include:

- University of Texas at Austin communities reached through the College of Fine Arts—including the Department of Arts and Entertainment Technologies—as well as general university outreach and Texas Exes.  
- The Dolph Briscoe Center for American History at the University of Texas at Austin, which is already preserving DECWAR artifacts and may host an exhibition devoted to the game in 2027\.  
- Computer-history museums and their communities, including the Computer History Museum, the Rhode Island Computer Museum, the Large Scale Systems Museum, and the UK’s National Museum of Computing and Centre for Computing History. Potential outreach could include author talks, demonstrations of the playable game, museum newsletters, and museum bookshops.  
- YouTube shows such as The 8-Bit Guy and LGR, and podcasts such as The Retro Hour, This Week in Retro, and Retro Computing Roundtable, as potential outlets for interviews and demonstrations of the game.  
- The Vintage Computer Federation, its regional festivals and online communities, and the ClassicCmp CCTalk mailing list.  
- The Video Game History Foundation and the International Center for the History of Electronic Games at The Strong.  
- The ACM History Committee, the IEEE Computer Society, and readers of IEEE Annals of the History of Computing.  
- SIGCIS, the Special Interest Group for Computing, Information, and Society, and its members’ listserv.  
- The Society for the History of Technology, including its newsletter and annual meeting.  
- The Digital Games Research Association and its conferences and regional chapters.  
- The Society for Cinema and Media Studies’ Video Game Studies Scholarly Interest Group.  
- The Association of Internet Researchers and its AIR-L mailing list.  
- Decwar.org, former DECWAR and MegaWars players, PDP-10 preservation and emulation communities, and groups devoted to CompuServe and early online services.

## Status of the Book

The manuscript is now in the early stages of writing. The team has already assembled substantial supporting material, including source code, historical documentation, archival materials, photographs, gameplay records, and completed interviews. The game’s recovery and reconstruction have also established a strong technical foundation for the book. Several major interviews with DECWAR’s creators, developers, and players remain to be conducted, and additional archival research and analysis will continue as the manuscript is written.

The authors expect to complete the manuscript within twelve months of receiving a contract.  
The completed manuscript is expected to be approximately 75,000–80,000 words, corresponding to roughly 300–350 finished pages, depending on trim size, figure placement, and the treatment of notes and back matter. This length will allow for a substantial treatment of DECWAR’s history, design, gameplay, commercial life, and reconstruction while remaining accessible to a broad audience interested in games, software, and computing history.

The book is expected to contain approximately 20 figures, including period photographs, archival documents, source-code excerpts, and diagrams explaining the game’s architecture, operation, and historical development. It will also include about 20–30 gameplay images, including terminal sessions and screenshots from historical and modern implementations. Rights and reproduction permissions will need to be researched and secured for some historical photographs.

## Reviewers

The following reviewers offer expertise in the book’s subjects or firsthand knowledge of its history:

**Jesse Schell**, CEO of Schell Games and Distinguished Professor of Entertainment Technology at Carnegie Mellon University’s Entertainment Technology Center, is a leading game designer, educator, and author of *The Art of Game Design*. He would be a valuable reviewer for a platform-studies / game-history treatment of DECWAR and early multiplayer software culture. Professional acquaintance: we have discussed DECWAR with him previously but have not secured his involvement as a reviewer.

**Bob Hysick**, co-developer of DECWAR, brings first-hand knowledge of the game’s design, implementation, and early multiplayer culture at UT Austin. He would be an especially valuable reviewer for technical and historical accuracy in a platform-studies treatment of the system. We are in touch with him, but have not asked him to review. The other co-developer, **Jeff Potter**, whereabouts are currently unknown.

**Bill Louden** is an early online / MMOG industry pioneer: founding member at CompuServe who designed and developed MegaWars (1982) from DECWAR — widely cited as the first commercial multiplayer game, running \~18 years — and later founder and president of GEnie at GE, where related titles continued as Stellar Warrior. I am currently in touch with Bill but have not asked him to review this proposal.

# 

# Detailed Annotated Table of Contents

**Working title:** *DECWAR: How a University Mainframe Became a Multiplayer Galaxy*

## Prologue: The Shared Galaxy

The book opens inside a game of DECWAR. At separate terminals, a roomful of players command individual starships within the same live galaxy. They scan space, capture planets, build starbases, cause supernovas, battle the opposing faction, and communicate by subspace radio—all through typed commands.

The scene introduces the book’s central question: how did programmers in 1978 turn a university mainframe intended for institutional computing into a compelling multiplayer world? The prologue establishes what playing DECWAR felt like before explaining the technical and historical conditions that made it possible. Any reconstructed gameplay will be clearly identified rather than presented as a surviving contemporaneous transcript.

# Part I: The World That Made DECWAR

## 1\. *Playing Star Trek*

While the original Star Trek series ended in 1969, reruns helped it find new fans throughout the 1970s. For programmers, its starships, computer consoles, galactic maps, and space battles were full of possibilities for games. At a time when few people had computers of their own, students and programmers began making text-based games inspired by the show on machines at schools, universities, and research centers.

One of the most influential was Mike Mayfield’s BASIC Star Trek. Its source code appeared in books and magazines. Readers could type it in, play it, see how it worked, and change existing features. As programmers shared the game, entirely new versions were created. All the variants shared the same basic features: a galaxy drawn in text, typed commands, navigation, scanning, energy management, and combat with Klingons. Programmers built on these ideas, each taking the game in a different direction.

At the University of Texas at Austin, programmers took these games in a new direction. Dave Matuszek and Paul Reynolds developed an expanded FORTRAN version for the university’s CDC system. A later game, WAR, allowed two people to play against each other rather than against the computer. Robert Schneider began adapting WAR for the university’s DEC-10, where Jeff Potter and Bob Hysick would develop it into DECWAR. The chapter traces the evolution of Star Trek-style text games, leading up to the creation of DECWAR at UT.

## 2\. Computing in 1978

In 1978, access to a powerful computer usually meant access to an institution that could afford one. At the University of Texas at Austin, the Computation Center brought together expensive machines, specialist staff, researchers, and students. Alongside scientific and administrative work, programmers wrote their own tools, traded ideas, and stayed late to experiment. Games grew out of this mixture of institutional resources and personal curiosity.

Computing was also becoming more immediate and accessible. Users could sit at terminals and interact with programs rather than submit punched cards and wait for results. Time-sharing let many people use one machine, while remote connections extended access beyond the computer center. UT’s regional educational network served other institutions, and ARPANET connected the university to a wider experiment in networked computing.

UT’s DEC-10, which arrived in the mid-1970s, gave this community another place to work and play. This PDP-10 system let people work at separate text terminals, with the TOPS-10 operating system dividing the machine’s attention among their jobs. The chapter walks readers through computing as it was experienced at the time, exploring the capabilities of the PDP-10 and the networks that were changing how people reached and used computers.

# Part II: Building and Playing the Galaxy

## 3\. From WAR to DECWAR

DECWAR began with an effort to move a game between two very different computers. Robert Schneider rewrote the two-player WAR and began adapting it from the university’s CDC system to the DEC-10. Jeff Potter and Bob Hysick took that work further, redesigning and almost entirely rewriting the game to support more players, more commands, and real-time play.

Working in FORTRAN and MACRO-10 assembly, they gave each player’s starship its own TOPS-10 job and used shared memory to hold the galaxy. Players at separate terminals could now act independently while affecting the same world. The chapter follows the decisions and experiments that made this possible, drawing on the surviving code and the programmers’ accounts of their work.

Hysick’s recollections of late-night development and access to a prized 9,600-baud terminal bring readers into the working environment. From the first installation in 1978 through later university versions, the chapter follows how Potter, Hysick, other contributors, and their players helped DECWAR take shape.

*Research note: We are still assembling the detailed story of DECWAR’s creation. We have access to co-creator Bob Hysick, but a substantial interview remains to be conducted. The depth and shape of the development narrative will depend on what that interview and further research reveal.*

## 4\. Playing DECWAR

The chapter follows a player into DECWAR: joining a galaxy already in progress, choosing a side and ship, and learning to read the screen and issue commands. Readers learn how to navigate, scan their surroundings, manage energy, dock, repair damage, communicate, and fight. Each action introduces another part of the game and the choices a player has to make.

As play unfolds, those choices become more complicated. Federation and Empire players capture planets, build and defend starbases, fire torpedoes and phasers, cause supernovas, and coordinate attacks. Black holes, damaged equipment, and delays can upset their plans. The chapter examines the careful balance of space, energy, time, and damage: how players choose their positions, use limited resources, and weigh an attack against the need to retreat and repair. It also explores the role of the automated Romulan and how its presence shapes players’ decisions. Throughout, readers encounter the peculiarities that experienced players learned to anticipate or exploit.

DECWAR’s command language is part of that experience. Players could shorten commands, combine them, and repeat them quickly as they became more fluent. The chapter explores how those commands, the information returned on screen, and radio messages from other players made a shared galaxy understandable and compelling. Screenshots and reconstructed play sessions let readers follow the action and its consequences, even if they have never played a game through a terminal.

## 5\. The Machine in the Game

In DECWAR, every player’s starship ran as a separate TOPS-10 job. The operating system divided the computer’s attention among those jobs, while shared memory held the galaxy they inhabited. This chapter explains how those pieces worked together: how one ship’s actions changed the world seen by others and how the game coordinated simultaneous activity. The chapter also examines the practical limits that affected play, including slow floating-point calculations and slow terminal communications. It looks at how the game loop accounted for differences in players’ connection speeds, and how these constraints and adjustments shaped the game’s pace and balance.

We’ll also examine the FORTRAN and MACRO-10 assembly programming languages, which were used together to implement the game’s rules and control its interaction with the PDP-10. Short code excerpts and diagrams connect these mechanisms to familiar moments in play, giving readers a way to understand the implementation without needing to know either programming language.

## 6\. The Language of the Game

DECWAR’s text-only, command-driven form lends itself to the kind of precise analysis used to describe a programming language. This chapter examines how commands are formed and interpreted, and how their execution changes the game’s state. The focus is on the relationship between what a player types and what happens in the shared galaxy, including how timing and other players’ actions affect the outcome.

Formal descriptions, annotated source excerpts, and worked examples explain the logic implemented in FORTRAN and MACRO-10. They show how interacting rules produce the game’s distinctive behavior, including its unexpected consequences and exploitable peculiarities. The chapter also examines differences between the documented rules and the surviving implementation, providing a precise account of how DECWAR actually works

# Part III: Beyond Austin

## 7\. The Social Galaxy

A DECWAR game could bring together a roomful of players and others connecting from elsewhere. Some could hear their opponents reacting across the room; others knew them through their ships and radio messages. Players learned one another’s habits, formed rivalries, developed strategies, and called on teammates for help. The people in the galaxy gave each game a different character.

Interviews with players at the University of Texas, Southwest Texas State University, Kentucky institutions, and other sites will help tell the story of these communities. We’ll examine how newcomers learned to play, how experienced players earned reputations, and how groups developed their own customs. Players also had a relationship with the people maintaining the game, using its built-in complaint system to report problems and respond to changes.

These accounts will help explain why DECWAR was so compelling during the rise of graphical video games. Its world was made entirely from text, but the competition, cooperation, and uncertainty came from other people. The chapter explores how players experienced that shared world and why they remembered it long afterward. Comparisons with other early multiplayer games will place those experiences within the wider emergence of online play.

## 8\. Compuserve and MegaWars

DECWAR left Austin on magnetic tapes that the University of Texas distributed for fifty dollars, complete with source code, documentation, and the tools needed to install the game. A copy reached CompuServe, an early commercial online service whose customers connected through home computers and modems. There, DECWAR was adapted, given a new presentation, and stripped of its explicit Star Trek references. As MegaWars, it became a commercial offering that remained viable for roughly fifteen years.

The chapter follows that transformation, examining what changed when a university game became a service people paid to play. Comparisons of DECWAR, the early CompuServe version, and MegaWars will look beyond names and presentation to differences in rules, mechanics, balance, and the experience of playing, alongside connection costs, customer support, and the expectations of a new audience. Surviving code, documentation, player accounts, and planned interviews with Bill Louden and other CompuServe participants will help explain how the game found a lasting place in commercial online entertainment.

## 9\. DECWAR in Game History

This chapter places DECWAR within the broader history of games, with particular attention to its place as a very early example of multiplayer play in a shared space—a world that separate players could inhabit and change simultaneously. Drawing on historical scholarship, it compares DECWAR with earlier and contemporary text-based games, combat and strategy games, and multiplayer systems. It examines how these games organized space, time, and conflict, and how DECWAR’s design relates to the different approaches being explored during this period.

DECWAR’s combination of individual starship control, territorial conquest, and team objectives connects it to both tactical combat and larger-scale strategy games. Its simultaneous play offers a comparison with games organized around turns, while its command-driven interface belongs to a period when text-based and graphical games were developing alongside one another. The chapter uses these comparisons to examine DECWAR’s place in the development of game design, identifying established conventions, departures from them, and connections supported by the historical record.

# Part IV: Saving the Galaxy

## 10\. Recovering DECWAR

The chapter follows the recovery of DECWAR’s code, from Harris Newman’s search and the mysterious email to the work of making the surviving software run under PDP-10 emulation. Along the way, it asks which parts of the surviving code came from the University of Texas, which were changed or added at CompuServe, and how those layers can be separated from later restoration work. Recovering the game meant understanding these differences, reassembling its development environment, and working through the problems that prevented it from running. The story brings together the people who preserved the files and the technical work that made them playable again.

## 11\. Porting the Game

With the historical game running, the next challenge is to build it anew using modern technology. This chapter follows the analysis of more than 20,000 lines of FORTRAN and MACRO-10 assembly, including the use of AI to help interpret the game’s syntax, semantics, and behavior. A precise specification, comparisons with the running historical implementation, and testing guide the development of the new version. The chapter explores what it takes to reproduce DECWAR’s rules, timing, shared world, and peculiarities in a different computing environment—and what that process reveals about the original game.

## Epilogue: The Galaxy Reopens

The epilogue returns to the experience of playing DECWAR. Former players revisit a game they remember, while students and newcomers encounter its galaxy for the first time. Their experiences offer a chance to consider what still makes the game compelling, what feels unfamiliar today, and how much of its character comes from the people playing it. The historical implementation running under emulation and the new version built with modern technology give readers ways to explore those questions themselves.

DECWAR’s journey began with programmers finding new possibilities in a university computer and grew through the people who played, shared, changed, and preserved it. Making the game publicly available alongside the book opens another chapter in that history. It may bring former players together, introduce new ones, and allow a community to form around the game again. The book closes with that possibility: a galaxy whose future is once more in its players’ hands.

