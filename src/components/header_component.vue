<template>
  <header>
    <ul>
      <li>
        <a href="#">Produtos</a>
      </li>
      <li>
        <a href="#">Clientes</a>
      </li>
    </ul>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  header {
    padding: 32px ;
    background-color: var(--primary-color);
    ul {
      width: inherit;
      height: inherit;
      
      display: flex;
      justify-content: flex-start;
      
      list-style-type: none;
      li {
        height: 100%;
        max-width: 180px;
        padding: 0 16px;
        display: flex;
        align-items: center;
        box-sizing: border-box;
        font-size: 20px;
        line-height: 20px;
        
        transition: 0.2s;
        &:hover {
          filter: brightness(0.9);
        }
        
        a {
          color: var(--white);
          font-size: var(--title-regular);
          text-decoration: none;
        }
      }
    }
  }
</style>