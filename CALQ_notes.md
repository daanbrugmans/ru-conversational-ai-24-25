# CALQ Notes

## Template
**C**ore quote(s):

**A**rgument(s):

**L**ink: 

**Q**uestion(s): 

## Paper 2: Computing machinery and intelligence, by A. M. Turing
**C**ore quote(s):
- "What will happen when a machine takes the part of A in [the imitation] game?" Will the interrogator decide wrongly as often when the game is played like this as he does when the game is played between a man and a woman? These questions replace our original, 'Can machines think?""
- "Let us fix our attention on one particular digital computer C. Is it true that by modifying this computer [...], C can be made to play satisfactorily the part of A in the imitation game, the part of B being taken by a man?"

**A**rgument(s): dr. Turing explores the concept of machine intelligence and how that may be defined.
He formulates the initial question of "Can machines think?" in such a way that we do not have to ponder about the definitions of "machines" and "think", but so that we can instead focus on trying to answer this question by using a hypothetical scenario called the "imitation game", nowadays called the Turing test, where a human interrogator attempts to correctly guess who of two people is a man and who is a woman, while only being able to communicate with them in a way that does not give away their identities.
While the imitation game would normally be performed by a set of three people, dr. Turing proposes that a (digital) computer may be able to substitute the role of the man, who normally attempts to deceive the interrogator into thinking they are a woman, but instead of two people attempting to convince the interrogator that they are not men, the computer and a human attempt to convince the interrogator that they are not computers; if the interrogator cannot correctly guess which is the computer, the computer wins the game.

The argument that dr. Turing makes here, in my view, would be this: if a computer could succeed at winning the imitation game reliably, meaning that a human interrogator would be unable to reliably conclude which of the participants is and isn't human, then it could be said that the computer's communicative abilities are on-par with a human's, and it could be said that that computer is able to act indistinguishably from a human participant.

**L**ink: The implications of the imitation game are very relevant to the course: a machine that passes the Turing test would be indistinguishable from a human, but that does not necessarily mean that it is the same as a human or works the same as a human.
Having a conversation with an artificial intelligence that can pass the Turing test may deceive the human participant into thinking that they are having a conversation with something that is human-like, despite that not being the case.
We have seen this happening with both ELIZA and ChatGPT, for example.
When designing conversational AI applications, we must keep in mind that the AI can *act like* or *talk like* a human *without actually **being*** human.
We must keep the sentiment of human users that may be deceived by the AI's human-like capabilities in mind by providing them with explanations on how the machine/computer/LLM works.

**Q**uestion(s): 
- Could we say that Weizenbaum's ELIZA has succeeded at the imitation game as Turing had described it? Since ELIZA was able to convince some people to think that it was human, one could say that it was able to pass the Turing test. How about ChatGPT when *it* was newly introduced to the public?
-  Not necessarily a question, but a potential point of discussion would be about the Chinese Room Experiment as a reaction to the imitation game.

## Paper 5: Turn-taking in Conversational Systems and Human-Robot Interaction A Review, by G. Skantze
**C**ore quote(s):
- The coordination of when a turn will transition, and who will speak next, relies on multiple signals across different modalities, including syntax, pragmatics, prosody and gaze.
- [...] [D]espite this progress in computational modelling of turn-taking, it is interesting to note how simplistic turn-taking models in most state-of-the-art conversational systems still are.

**A**rgument(s):
Dr. Skantze does not necessarily attempt to argue for a certain view.
In this paper, he offers the reader overviews of research and advancements within the field of turn-taking in conversation and the varying aspects of the turn-taking process that must or may be accounted for when developing conversational computer systems.
Dr. Skantze opens with an explanation of the fundamental concepts of turn-taking, and follows up by elaborating on the cues given during a conversation that may indicate a turn-taking-related phenomenon.
Specifically, he explains the varying types of cues in turn-taking, including syntax, semantics, pragmatics, prosody, gaze, gestures, and breathing, and talks about the existing research done on these turn-taking cues and what researchers have found in regards to how specific cues are used for specific purposes, such as turn-yielding cues and turn-holding cues.
Finally, dr. Skantze talks about four different problems that a conversational computer interface will face:
1. Picking up on turn-yielding cues, knowing which cues do and do not yield turns;
2. Coping with backchannels and other user interruptions;
3. Generating turn-yielding cues for the human speaker; and
4. Coping with turn-taking in multi-party and situated interactions.

**L**ink: 
The link this paper has with the course is very clear: this paper provides an extensive overview of the varying aspects designers and engineers of conversational computer systems must be aware of.
It is important that the students of the course, in preparation of the course's project, are aware of the challenges in turn-taking that they will encounter when working on the conversational AI they will build, and that they know the existing terminology for turn-taking research.
Furthermore, the paper may help the students in finding existing solutions to their problems and potential improvements to their conversational AI.

**Q**uestion(s): 