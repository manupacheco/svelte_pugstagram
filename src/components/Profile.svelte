<script>
  export let nickname;
  export let name;
</script>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="Profile">
  <div class="Profile-content">
    <div class="Profile-avatar">
      <img
        src="https://static.platzi.com/media/avatars/avatars/manupacheco_34a1f7a3-eb09-4054-8741-f3c31e1358aa.png"
        alt="user" />
    </div>
    <div class="Profile-info">
      <h2>@emeeneu</h2>
      <span>Manu Pacheco</span>
    </div>
  </div>
</div>
