<template>
  <div class="home">
    <BottomNav />
    <Quote />
    <TreiPoezii />
    <Evenimente />
    <Foamea />
    <Videoteca/>
    <Video/>
  </div>
</template>

<script>
// @ is an alias to /src
import BottomNav from "@/components/Home/BottomNav";
import Quote from "@/components/Home/Quote";
import TreiPoezii from "@/components/Home/TreiPoezii";
import Evenimente from "@/components/Home/Evenimente";
import Foamea from "@/components/Home/Foamea";
import Videoteca from "@/components/Home/Videoteca";
import Video from "@/components/Home/Video";

export default {
  name: 'Home',
  components: {
  BottomNav,
    Quote,
    TreiPoezii,
    Evenimente,
    Foamea,
    Videoteca,
    Video
  }
}
</script>
