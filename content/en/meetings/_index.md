---
title: Meetings
menu: {main: {weight: 30}}
cascade: [{
      "type": "blog"
    }]
---

{{< blocks/cover color="primary" title="Meetings" image_anchor="top" height="full">}}


<ul>

<li style="cursor:pointer;" id="kickoffmeeting">
Kickoff Meeting
</li>
</ul>

<script>
  // Get a reference to the clickable SVG element
  var clickableElement = document.getElementById("kickoffmeeting");
  
  // Add a click event listener to the element
  clickableElement.addEventListener("click", function() {
    // Redirect to the desired URL
    window.location.href = "/meetings/kickoff.md";
  });
</script>

{{< /blocks/cover >}}

