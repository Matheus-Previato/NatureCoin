<template>
    <button class="primary-btn">
      <slot></slot>
    </button>
  </template>
  
  <script>
  export default{}
  </script>
  
  <style scoped>
  .primary-btn {
      all: unset;
      cursor: pointer;
      background-color: #FFFFFF;
      border: 1px solid #FFFFFF;
      color: #166534;
      border-radius: 0.25rem;
      text-align: center;
      padding: 0.25rem 0.5rem;
  }
  
  .primary-btn:hover {
    background-color: #15803D;
    color: #FFFFFF;
    border-color: #FFFFFF;
    transition: background-color 0.3s ease;
    transform: scale(1.1);
  }
  </style>
  