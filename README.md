# css-frameworks-ma1
This is the first assignment in CSS frameworks and BEM classes. The design I were provided with was wasy enough to be recreated with just a few lines of SASS. Navigation is modified slightly, but no BEM needed. 
Will definetly use Bootstrap more in the future, due to the extreme amount of time saved.

Example of navigation with BEM:

<nav> //Block
  <ul class="nav__list"> //Element
    <li class="nav__item"> //Element
      <a href="index.html" class="nav__link nav__link--active"> //Element with modifier
    </li>
    <li class="nav__item">
      <a href="about.html" class="nav__link">
    </li>
  </ul>  
  
  //SASS makes it easy to nest everything with BEM classes.
  
  nav {
  &__list {
  &__item {
  &__link {
  &__link--active {
          }
        }
      }
    }
  }
