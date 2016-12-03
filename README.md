# PASC: "Protect and Serve... Capital"
Bringing Accountability to Police Brutality

## Problem:
  Currently, police routinely execute Americans, especially people of color, and face absolutely no negative consequences, often instead taking paid vacation, flaunting any concept of accountability. When they actually are charged with the crimes they committed, these aggressors instead are routinely deemed innocent. The names and faces of the murderers are infrequently made public, leaving the community to live in the presence of a commonly anonymous blank-check murderer with effective immunity. These events happen both in the course of "routine community policing" and in cataclysmic moments like the current #NODAPL protest. In these cataclysmic cases, the communities paying the taxes to fund the aggressor deployment don't necessarily even know what is being done in their name.

  With increasing frequency, these attacks are recorded on video: sometimes via the cell phones of friends, family, or acquaintances of the victims, sometimes via the cameras of news reporters, security cameras of local buisnesses, or, hopefully soon, by whatever means by which we at STEMAO can help by our own supporters of protests. This undeniable footage has proved potent in convincing those with priviledge to mobilize. The preservation of this footage holds the potential for future justice, for tracking the assailants involved and linking together multiple acts of violence without relying on rosy, coarse, conjured statistics from the enablers of this brutality. 
  
  Due to the importance of this footage, cell phones of recorders of police violence are simply taken or destroyed by police. Pressure is put on major communication platforms, such as Facebook, Twitch, or Youtube, to block streams or media from being propogated, and they routinely obey, for reasons we cannot fathom. Partiicular effort is put into targeting those with the power to spread footage to a wider audience; reporters are arrested and harrassed, major activists face sudden bans at critical moments from (ostensibly neutral) social media platforms.

## Relevant Technologies
  In this problem exist subproblems where we can help significantly. Of particular importance are the following already-or-imminently-existing technologies for the MVP (minimum viable product), the basic functionality necessary for an initial launch.
  
### MVP
  - **Distributed filesystems** such as [IPFS](https://ipfs.io/) allow for completely decentralized, content-addressed storage of footage, making it accessible as long as anybody anywhere cares about it.
    - This means there is no single server or person who controls distribution, or who everybody comes to for the data. This means no platform or organization can prevent the propogation of the footage.
    - Being content-addressed means any change to the video results in a different version, yet both can be accessed independently regardless. This makes modification of the video impossible to hide, allowing access to the original video regardless of possible attempts at misinformation that would otherwise be a risk in a decentralized architecture.
  - **Encrypting the video footage** prior to distribution with a newly-generated private key, then releasing the key publicly after the police department releases an official statement, so that distribution of the video can happen immediately, and all of them can be viewed only after the key is released
    - This would prevent the police from adapting their story to fit the video, instead catching them in the inevitable lie, while still benefiting from immediate distribution of the proof, albeit in a locked form.
    - The private key could be either held locally (which risks destruction) or instead handed off promptly to (potentially multiple) trusted third parties, local and trusted organizers or community leaders, or members in the relevant community, who could then choose when to release the keys publicly and unlock the footage for maximal impact.
    
### Possible Extensions
  As videos accumulate, including those hosted on other platforms, repeat oppressors can potentially start to be noticed, other public media/footage can be matched to assailant faces seen in the videos, and a record of assaults and executions sheet can potentially be assembled, linked to the relevant footage and other public information or media. Important, actionable information such as the contact information of the department or organization hosting said individual, their general location of deployment and associated local judicial officials, and collaborative efforts to organize demands for change and accountability can all also be associated. Interfacing with other projects and efforts to provide open data would be wise.
  
## Concrete Specification
~~ TO DO: this part ~~
