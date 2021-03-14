<template>
  <div class="task-list">
    <div class="task-card">
      <div class="card-icon">
        <desktop-icon></desktop-icon>
      </div>
      <div class="card-body">
        <div class="card-body-header">UI Design</div>
        <div class="task-tags">
          <div class="task-tag">Work</div>
          <div
            class="task-tag"
            style="background-color: #F5EEFC; color: #9B51E0"
          >
            Rasion Project
          </div>
        </div>
      </div>
      <div class="card-action">
        <div class="card-action-time">00:42:21</div>
        <play-icon></play-icon>
      </div>
    </div>
    <div class="task-card">
      <div class="card-icon" style="background-color: #FFA656">
        <barbell-icon></barbell-icon>
      </div>
      <div class="card-body">
        <div class="card-body-header">100x Sit-Up</div>
        <div class="task-tags">
          <div
            class="task-tag"
            style="background-color: #E5E5E5; color: #828282"
          >
            Personal
          </div>
          <div
            class="task-tag"
            style="background-color: #FEF5ED; color: #FFA656"
          >
            Workout
          </div>
        </div>
      </div>
      <div class="card-action">
        <div class="card-action-time">00:42:21</div>
        <play-icon></play-icon>
      </div>
    </div>
    <div class="task-card">
      <div class="card-icon" style="background-color: #FD5B71">
        <coding-icon></coding-icon>
      </div>
      <div class="card-body">
        <div class="card-body-header">Learn HTML & CSS</div>
        <div class="task-tags">
          <div
            class="task-tag"
            style="background-color: #E5E5E5; color: #828282"
          >
            Personal
          </div>
          <div class="task-tag">Coding</div>
        </div>
      </div>
      <div class="card-action">
        <div class="card-action-time">00:42:21</div>
        <play-icon></play-icon>
      </div>
    </div>
    <div class="task-card">
      <div class="card-icon" style="background-color: #07E092">
        <book-icon></book-icon>
      </div>
      <div class="card-body">
        <div class="card-body-header">Read 10 pages of book</div>
        <div class="task-tags">
          <div
            class="task-tag"
            style="background-color: #E5E5E5; color: #828282"
          >
            Personal
          </div>
          <div
            class="task-tag"
            style="background-color: #E6FCF4; color: #07E092"
          >
            Reading
          </div>
        </div>
      </div>
      <div class="card-action">
        <div class="card-action-time">00:42:21</div>
        <play-icon></play-icon>
      </div>
    </div>
  </div>
</template>
<script>
import DesktopIcon from "@/components/icons/desktop-icon.vue";
import PlayIcon from "@/components/icons/play-icon.vue";
import BarbellIcon from "@/components/icons/barbell-icon.vue";
import BookIcon from "@/components/icons/book-icon.vue";
import CodingIcon from "@/components/icons/coding-icon.vue";

export default {
  components: {
    DesktopIcon,
    PlayIcon,
    BarbellIcon,
    BookIcon,
    CodingIcon,
  },
};
</script>