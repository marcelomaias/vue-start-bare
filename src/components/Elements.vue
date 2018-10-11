<template>
  <div class="flex flex-50">
    <div>
      <section>
        <h1>First Header h1</h1>
          <p class="test-class">
            At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis
            praesentium voluptatum deleniti atque corrupti quos.
          </p>
          <h2>Second header h2</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
            tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
            quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
            consequat.
          </p>
          <h3>Third header h3</h3>
          <p>
            At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis
            praesentium voluptatum deleniti atque corrupti quos dolores et quas
            molestias excepturi.
          </p>
          <h4>Fourth header h4</h4>
          <p>
            Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet,
            consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt
            ut labore et dolore.
          </p>
        </section>
        <section>
          <h2>Unordered list</h2>
          <ul>
            <li>Orange</li>
            <li>Apple</li>
            <li>Rhubarb</li>
            <li>Rasberry</li>
            <li>Blueberry</li>
            <li>Cherry</li>
          </ul>
          <h2>Ordered list</h2>
          <ol>
            <li>First</li>
            <li>Second</li>
            <li>Third</li>
            <li>Fourth</li>
            <li>Fifth</li>
            <li>Sixth</li>
          </ol>
        </section>
      </div>
      <div>
        <section>
          <h1 class="other-class">Links</h1>
          <a href="#">Sample text link</a>
          <a href="#">Sample button link</a>
        </section>
        <section>
          <h1 class="other-class">Buttons</h1>
          <button>A button</button>
          <button>A button</button>
          <button>A large button</button>
        </section>
        <section>
          <h1 class="other-class">Forms</h1>
          <form>
              <section>
                <label>Text Input Label</label>
                <input type="text" />
                <p class="test-class">Helper text if necessary.</p>
              </section>
              <section>
                <label>Password</label>
                <input type="password" />
                <p class="test-class">Error messages when appropriate.</p>
              </section>
              <section>
                <label for="first-name">First Name</label>
                <input type="text" id="first-name" />
              </section>
              <section>
                <label for="last-name">Last Name</label>
                <input type="text" id="last-name" />
              </section>
              <section>
                <label for="email">Email</label>
                <input type="email" id="email" />
              </section>
              <section>
                <label for="gender">Dropdown</label>
                <select>
                  <option>Option 1</option>
                  <option>Option 2</option>
                  <option>Option 3</option>
                </select>
              </section>
              <section>
                <label>Radio Buttons</label>
                <div>
                  <input type="radio" id="radio1" name="radio1" />
                  <label for="radio1">Radio 1</label>
                </div>
                <div>
                  <input type="radio" id="radio2" name="radio2" />
                  <label for="radio2">Radio 2</label>
                </div>
                <div>
                  <input type="radio" id="radio3" name="radio3" />
                  <label for="radio3">Radio 3</label>
                </div>
              </section>
              <section>
                <label for="url">URL Input</label>
                <input type="url" placeholder="http://mrmrs.cc" />
              </section>
              <section>
                <label>Text area</label>
                <textarea></textarea>
              </section>
              <section>
                <input type="checkbox" id="check1" name="check1" /> 
                <label for="check1">This is a checkbox.</label>
              </section>
              <section>
                <input type="submit" value="Submit" />
              </section>
          </form>
        </section>
      </div>
    </div>
</template>

<script>
export default {
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
