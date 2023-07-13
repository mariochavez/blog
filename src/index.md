---
# Feel free to add content and custom Front Matter to this file.

layout: default
---

## Bienvenido a mi blog personal

En este blog encontrarás mis publicaciones sobres temas de tecnología que me interesan y me motivan.

Mis intereses principales son en el lenguaje **Ruby** y tecnologías para el desarrollo de aplicaciones Web.

Si alguna de mis publicaciones te es útil, agradeceré que la compartas con otras personas.

#### PUBLICACIONES RECIENTES

Aquí tienes mis publicaciones recientes.

<div class="mt-10 space-y-10 border-t border-gray-200 pt-10 not-prose">
  <% collections.posts.resources[0..4].each do |post| %>
    <%= render Shared::PostItem.new(post: post) %>
  <% end %>
</div>
