---

# Jekyll
layout: event

# Event info
name: "Sample event 3"
location: ""

short-description: "This is a sample event."
display-date: "2022-02-21"

is-public: true # Makes this event visible in events list

start: "2099-01-01T12:00:00+00:00"
end: "2001-01-01T12:00:00+00:00"

full-description: ""

# Styling
color: "#EB6824"

# Jumbotron
display-logo: false
small-logo: "rh-small.svg"
logo-width: 1
jumbotron-image: ""
jumbotron-image-adjust: "rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)"


show-ticket-button: true
disable-button: true
tickets: "https://eventbrite.com"
ticket-button-text: "RSVP"

show-sponsors-list: true
sponsors:
    -
      Name: "Example"
      Link: "https://www.example.com/"
      Icon: "rh-small.svg"
      Colour: #A60000
    -
      Name: "Example2"
      Link: "https://www.example.com"
      Icon: "rh-small.svg"
      Colour: #A60000

---


<section id="event-extra-content" style="background-color: {{ page.color }}">
  <div class="container text-light">
 <p class=""> this is some example extra content.</p>
</section>


This is some extra example content.
