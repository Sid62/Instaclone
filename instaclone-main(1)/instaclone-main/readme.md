login & register page
feed page
profile page
picture
story feature
edit details
share to story
search accounts

 <% user.posts.forEach(function(post){ %>
            <div class="post w-[32.5%] h-32 bg-sky-100 overflow-hidden">
              <img class="post w-full h-full object-cover" src="/images/uploads/<%=post.picture%>" alt="">  
  
            </div>
            <%  }) %>