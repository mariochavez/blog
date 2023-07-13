---
layout: page
title: Mis publicaciones
description: Listado de las publicaciones realizadas en mi blog.
---

<div class="mt-10 space-y-10 border-t border-gray-200 pt-10 not-prose">
  <% collections.posts.resources.each do |post| %>
    <%= render Shared::PostItem.new(post: post) %>
  <% end %>
</div>
