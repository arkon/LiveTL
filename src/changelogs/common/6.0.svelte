<script>
  import { ExpansionPanel } from 'svelte-materialify';
</script>

<ExpansionPanel>
  <span slot="header">A complete redesign from scratch!</span>
  This version integrates Material UI components. Enjoy a new, modern interface with
  buttery smooth animations! Also, the internals of the entire extension have been
  rewritten from scratch. No longer do you have to deal with the janky mechanics
  and bugs of previous versions!
</ExpansionPanel>
<ExpansionPanel>
  <span slot="header">Embedded mode</span>
  You can now load LiveTL right within the YouTube interface without using the popout
  mode.
</ExpansionPanel>
<ExpansionPanel>
  <span slot="header">New filter options</span>
  LiveTL now has advanced filtering options like username/message filters in both
  plaintext and regex! Check them out in the "Filters" tab in the settings menu.
</ExpansionPanel>
<ExpansionPanel>
  <span slot="header">Available for iOS, Android, Edge, Opera, and more</span>
  <p>
    LiveTL is now available for Chrome, Firefox, Android, iOS, Opera, Brave, and
    any Chromium-based platform! You can find all download links
    <a href="https://livetl.app" target="_blank">on our website</a>.
  </p>
</ExpansionPanel>
<ExpansionPanel>
  <span slot="header">Automatic live translations are coming soon!</span>
  <p>
    For the past few months, our team has been hard at work on a project called
    Kanatran (KT) that translates Hololive streams in realtime. We already have
    the system up and running at a small scale, and with financial support from
    users like you, we can apply KT to more Hololive/Vtuber streams! If you are
    interested in funding this project, please consider
    <a href="https://opencollective.com/livetl" target="_blank"
      >chipping in through Open Collective</a
    >. (KT may become a paid or free feature, we aren't quite sure yet.)
  </p>
</ExpansionPanel>
