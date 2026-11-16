# Dawah Kit: live notices and weekly packs

Public files that every copy of the Dawah Kit reads at each run:

- `.status/live.json`: account notices and the newest Kit version, signed by the Kit's owner.
- `.packs/`: weekly packs (approved scholar clips and answering-doubts posts), signed with the pack key.

Every file here is signed; a Kit ignores anything whose signature does not check. Nothing secret is kept here.
