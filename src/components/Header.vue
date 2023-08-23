

<template>
    <header class="header">
      <h1 class="name">Melanie Molen</h1>
      <v-col style='right: 100px; position: absolute;'>
        <button class="button" style="">Projects</button>
        <button class="button">Resume</button>
        <button class="button">About Me</button>
      </v-col>
    </header>
  </template>

<style>
.button {
  background-color: #059c9e;
  border: none;
  color: white;
  padding: 15px;
  width: 140px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 12px;
  margin-left: 50px;
  font-weight: bold;
  
}
.header {
  margin: 0;
  position: fixed;
  padding-top: 20px;
  min-width: 825px;
  color: white;
  
  
}
.name {
  display:inline; 
  padding-left: 30px; 
  top: 25px; 
  position: fixed;
  font-size: 32px;
  
}

</style>