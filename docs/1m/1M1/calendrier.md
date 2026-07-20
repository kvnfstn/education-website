# Calendrier 1M

<div id="calendar"></div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const calendarEl = document.getElementById('calendar');

  const calendar = new FullCalendar.Calendar(calendarEl, {
    initialView: 'dayGridMonth',

        
    headerToolbar: {
        left: 'prev,next',
        center: 'title',
        right: ''
    },


    locale: 'fr',
    events: [
      {
        title: 'Quiz Python',
        start: '2026-08-15'
      },
      {
        title: 'Projet Web',
        start: '2026-07-25'
      },
      {
        title: 'Examen',
        start: '2026-10-08'
      }
    ]
  });

  calendar.render();
});
</script>