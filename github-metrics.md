<h1 align="center">Hi, I'm Mune</h1>
<h3 align="center">I'm currently a student majoring in Information Technology at University of Information Technology</h3>
<img src="https://assets.mune.moe/images/banners/mune_banner_02.png" alt="Banner" width="100%" />

<%- await embed(`base`, { base: "header, activity, community, repositories"}) %>
<%- await embed(`isocalendar`, { isocalendar: true, isocalendar_duration: "full-year", config_display: "column" }) %>
<%- await embed(`achievements`, { achievements: true, achievements_display: "detailed", achievements_secrets: "yes", achievements_threshold: "X"}) %>
