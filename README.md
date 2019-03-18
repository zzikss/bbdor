# BBdor Project

Let the script speak to build your teams !!

## Parameters

- participants : list of participants
> participants=[{"name":"Participant 1"},{"name":"Participant 2"},{"name":"Participant 3"}]
- html-elements : You can define all the internal HTML from their HTML id
> html-elements=[{"id":"idValue", "innerHTML":"newValue"},{"id":"idValue2", "innerHTML":"newValue2"]
- style : You can override CSS style
> style=".classExemple{color:red;}"



You must encode all the characters in the parameters : https://meyerweb.com/eric/tools/dencoder/


### Exemple :
> https://zzikss.github.io/bbdor/?participants=[{"name":"Participant1"},{"name":"Participant2"},{"name":"Participant3"},{"name":"Participant4"},{"name":"Participant5"}]&html-elements=[{"id":"title","innerHTML":"BB d'or"},{"id":"subtitle","innerHTML":"C'est baby babou, c'est baby babou !!"},{"id":"submit-button","innerHTML":"Babyyyy"}]&style=html::after {background: url('https://images.pexels.com/photos/371633/pexels-photo-371633.jpeg') no-repeat center center fixed;}

Encode params
> https://zzikss.github.io/bbdor/?participants=[{%22name%22:%22Participant1%22},{%22name%22:%22Participant2%22},{%22name%22:%22Participant3%22},{%22name%22:%22Participant4%22},{%22name%22:%22Participant5%22}]&html-elements=[{%22id%22:%22title%22,%22innerHTML%22:%22BB%20d%27or%22},{%22id%22:%22subtitle%22,%22innerHTML%22:%22C%27est%20baby%20babou,%20c%27est%20baby%20babou%20!!%22},{%22id%22:%22submit-button%22,%22innerHTML%22:%22Babyyyy%22}]&style=html%3A%3Aafter {background%3A url('https%3A%2F%2Fimages.pexels.com%2Fphotos%2F371633%2Fpexels-photo-371633.jpeg')%3Bbackground-position%3A center%3Bbackground-repeat%3A no-repeat%3Bbackground-size%3A cover%3B}
