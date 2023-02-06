<template>
  <Page>
    <One v-for="n in 1" :key="n">
      <Two v-for="i in 1" :key="i">
        <Three v-for="k in 1" :key="k">
          <Onion v-for="g in 1" :key="g" />
        </Three>
      </Two>
    </One>
  </Page>
</template>
