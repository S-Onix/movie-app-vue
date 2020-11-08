<template>
  <v-app>
    <v-container>
      <!-- 검색바 -->
      <search-bar />
      <!-- 영화 목록 -->
      <movie-list />
    </v-container>
  </v-app>
</template>

<script>
// Vuetify 에서는 다폴트값으로 @ 를 통해 절대경로가 설정된다.
import SearchBar from '@/components/SearchBar'
import MovieList from '@/components/MovieList'

export default {
  components : {
    SearchBar,
    MovieList
  }
}
</script>
