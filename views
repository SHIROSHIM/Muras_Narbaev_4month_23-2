from django.contrib import admin
from django.urls import path
from posts.views import hello_world_view, datetime_view, goodbye_view

urlpatterns = [
    path('admin/', admin.site.urls),
    path('hello/', hello_world_view),
    path('now_time/', datetime_view),
    path('goodbye/', goodbye_view),
]
