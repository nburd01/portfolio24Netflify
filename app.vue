<template>
  <div class="gallery">
    <div class="card latched">
      <section
        class="card latched flex flex-col justify-start content-start bg-black p-0 sm:p-20 text-zinc-50"
      >
        <div class="headlineDiv h-3/3 sm:1/3 md:h-2/3">
          <h2 class="headline font-semibold">I'm Niall</h2>
          <h2 class="headline font-semibold">Portfolio/24</h2>
        </div>
        <nav>
          <ul class="menu">
            <NuxtLink
              class="li"
              :to="{ path: '/', hash: '#link' }"
              @click="scrollToSection('#link')"
            >
              <span> Projects </span></NuxtLink
            >
            <NuxtLink
              class="li"
              :to="{ path: '/', hash: '#contact' }"
              @click="scrollToSection('#contact')"
            >
              <span> Contacts </span></NuxtLink
            >
          </ul>
        </nav>
        <div>
          <div class="frontEndDeveloperDiv flex flex-col md:flex-row">
            <div class="frontEndDeveloper">
              <div class="flex sm:justify-start">
                <span class="flex m-3 md:m-0">Frontend Developer</span>
              </div>
              <div class="flex sm:justify-start">
                <span class="flex m-3 md:m-0">Digital Consultant</span>
              </div>
            </div>

            <div class="frontEndDeveloper">
              <div class="flex sm:justify-start justify-center">
                <span class="flex m-3 md:m-0">
                  ✺Here you can see some of my latest designs and projects</span
                >
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
    <div class="spacer"></div>

    <!-- INTRODUCTION TO ME -->
    <div class="card">
      <section class="card bg-white sm:p-11 h-lvh flex flex-col">
        <div class="container mx-auto px-0 sm:px-0 flex flex-col items-center">
          <div class="">
            <h1 class="aboutMeText text-black text-center">
              Crafting nice and useful things for people
            </h1>
          </div>
          <p class="whatIdo text-center text-black p-0 sm:px-24 py-5">
            An enriching experience in IT reinforced my desire to work more
            closely with the product and the organization of work. Today I
            aspire to a Front-end Developer or Product Owner position which will
            allow me to highlight this versatility acquired during my career in
            the field of innovation and the web.
          </p>
          <p class="whatIdo text-center text-black p-0 sm:px-24 py-5">
            I graduated from Business Administration and Marketing degree in
            IGR-IAE school of Management in Rennes, France.
          </p>
          <p class="whatIdo text-center text-black p-0 sm:px-24 py-5">
            Previously I had the opportunity to collaborate with the Fédération
            Française de Football where I focused on rebranding and marketing
            the entity, and also porposed and led the project.
          </p>
          <img src="assets/img/portrait.webp" class="portrait" alt="" />
        </div>
      </section>
    </div>
    <div class="spacer"></div>

    <!-- WHAT I DO -->
    <div class="card">
      <section class="card skillsDiv e6eaee sm:p-11 h-lvh">
        <div class="container contents">
          <div class="skills flex flex-col text-black">
            <span class="whatIDo">Product design</span>
            <span class="whatIDo">User experience</span>
            <span class="whatIDo">UI design</span>
            <span class="whatIDo">Visual design</span>
          </div>
        </div>
      </section>
    </div>
    <div class="spacer"></div>

    <!-- GSAP -->
    <div
      class="card roundedCard last-card bg-black w-full h-full text-center justify-center"
    >
      <!-- <section> -->
      <section>
        <div class="container flex align-center wrap">
          <h2 class="flex text-center justify-center headline">Recent work</h2>
        </div>
      </section>
    </div>
    <div class="spacer"></div>

    <!-- Rubrash-->
    <div class="card bg-black" id="link">
      <section class="card justify-center sm:sm:p-11 pt-0 h-lvh">
        <div class="container">
          <div
            class="content-baseline justify-start flex flex-wrap sm:sm:p-11 pt-0"
          >
            <NuxtLink to="https://rubrash.com/">
              <div class="mx-auto flex justify-center flex flex-wrap">
                <img class="projectImg" src="assets/img/rubrash.webp" alt="" />
              </div>
              <div class="container">
                <div class="project">Rubrash</div>
                <div class="project-description"></div>
                <div>✦ LARAVEL DEVELOPER / NUXT.JS</div>
                <!-- <font-awesome-icon icon="fa-solid fa-house" /> -->
              </div>
            </NuxtLink>
          </div>
        </div>
      </section>
    </div>
    <div class="spacer"></div>
    <!-- Roazhon Goal Academy-->
    <div class="card bg-black" id="link">
      <section class="card justify-center sm:sm:p-11 pt-0 h-lvh">
        <div class="container">
          <div
            class="content-baseline justify-start flex flex-wrap sm:sm:p-11 pt-0"
          >
            <NuxtLink to="https://roazhongoalacademy.fr/">
              <div class="mx-auto flex justify-center flex flex-wrap">
                <img class="projectImg" src="assets/img/rga.webp" alt="" />
              </div>
              <div class="container">
                <div class="project">Roazhon Goal Academy</div>
                <div class="project-description"></div>
                <div>✦ PRODUCT DESIGN / VISUAL DESIGN / CONCEPT</div>
                <!-- <font-awesome-icon icon="fa-solid fa-house" /> -->
              </div>
            </NuxtLink>
          </div>
        </div>
      </section>
    </div>
    <div class="spacer"></div>
    <!-- Centre Technique Bretagne -->
    <div class="card bg-black" id="link">
      <section class="card justify-center sm:sm:p-11 pt-0 h-lvh">
        <div class="container">
          <div
            class="content-baseline justify-start flex flex-wrap sm:sm:p-11 pt-0"
          >
            <NuxtLink to="https://centretechniquebretagne.com/">
              <div class="mx-auto flex justify-center flex flex-wrap">
                <img class="projectImg" src="assets/img/ctbhg.webp" alt="" />
              </div>

              <div class="container">
                <div class="project">Centre Technique Bretagne</div>
                <div class="project-description"></div>
                <div>✦ PRODUCT DESIGN / VISUAL DESIGN / CONCEPT</div>
                <!-- <font-awesome-icon icon="fa-solid fa-house" /> -->
              </div>
            </NuxtLink>
          </div>
        </div>
      </section>
    </div>
    <div class="spacer"></div>

    <!-- FOOTER -->
    <div class="">
      <footer id="contact" class="footerCard roundedCard bg-white h-24 flex">
        <!-- <div class="flex sm:p-11"> -->
        <div class="flex flex-col roundedCard justify-between bg-white z-10">
          <div class="container">
            <div class="flex flex-row justify-between sm:p-11">
              <h1 class="footerTitle text-black">
                Tell me something cool or just troll me.
              </h1>
              <div id="contactMe">
                <ul class="text-black">
                  <NuxtLink to="https://www.instagram.com/niallyyy_/?hl=fr">
                    <li>instagram</li>
                  </NuxtLink>
                  <NuxtLink to="https://linktr.ee/niallburdon">
                    <li>Linktree</li>
                  </NuxtLink>
                  <NuxtLink href="mailto:niall.burdon@gmail.com">
                    <li>email</li>
                  </NuxtLink>
                </ul>
              </div>
            </div>
            <div class="marquee bg-white sm:p-11">
              <div class="wrapper">
                <div class="box">
                  <div class="test">N</div>
                </div>
                <div class="box">
                  <div class="test">I</div>
                </div>
                <div class="box">
                  <div class="test">A</div>
                </div>
                <div class="box">
                  <div class="test">L</div>
                </div>
                <div class="box">
                  <div class="test">L</div>
                </div>
                <div class="box">
                  <div class="test">.</div>
                </div>
                <div class="box">
                  <div class="test">B</div>
                </div>
                <div class="box">
                  <div class="test-2">U</div>
                </div>
                <div class="box">
                  <div class="test">R</div>
                </div>
                <div class="box">
                  <div class="test">D</div>
                </div>
                <div class="box">
                  <div class="test">O</div>
                </div>
                <div class="box">
                  <div class="test">N</div>
                </div>
                <div class="box">
                  <div class="test">@</div>
                </div>
                <div class="box">
                  <div class="test">G</div>
                </div>
                <div class="box">
                  <div class="test">M</div>
                </div>
                <div class="box">
                  <div class="test">A</div>
                </div>
                <div class="box">
                  <div class="test">I</div>
                </div>
                <div class="box">
                  <div class="test">L</div>
                </div>
                <div class="box">
                  <div class="test">.</div>
                </div>
                <div class="box">
                  <div class="test">C</div>
                </div>
                <div class="box">
                  <div class="test">O</div>
                </div>
                <div class="box">
                  <div class="test">M</div>
                </div>
                <div class="box">
                  <div class="test"></div>
                </div>
                <div class="box">
                  <div class="test"></div>
                </div>
                <div class="box">
                  <div class="test"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- </div> -->
      </footer>
    </div>
    <div class="spacer"></div>
  </div>
</template>

<script setup>
import { onMounted } from "vue";
import { gsap } from "gsap";

onMounted(() => {
  //SCROLL
  var positions = [];
  var cards = document.querySelectorAll(".card");

  cards.forEach(function (card) {
    positions.push(card.getBoundingClientRect().top + window.scrollY);
  });

  window.addEventListener("scroll", function () {
    var pos = window.scrollY || window.scrollY;

    for (var i = 0; i < cards.length; i++) {
      if (pos >= positions[i]) {
        cards[i].classList.add("latched");
      } else {
        cards[i].classList.remove("latched");
      }
    }
  });
  const { innerHeight } = window;

  //ZOOM-OUT

  //MARQUEE
  const wrapper = document.querySelector(".wrapper");
  // const colors = ["#f38630"];
  const boxes = gsap.utils.toArray(".box");

  // gsap.set(boxes, {
  //   backgroundColor: gsap.utils.wrap(colors),
  // });

  const loop = horizontalLoop(boxes, { paused: false, repeat: -1 });
  function horizontalLoop(items, config) {
    items = gsap.utils.toArray(items);
    config = config || {};
    let tl = gsap.timeline({
        repeat: config.repeat,
        paused: config.paused,
        defaults: { ease: "none" },
        onReverseComplete: () =>
          tl.totalTime(tl.rawTime() + tl.duration() * 100),
      }),
      length = items.length,
      startX = items[0].offsetLeft,
      times = [],
      widths = [],
      xPercents = [],
      curIndex = 0,
      pixelsPerSecond = (config.speed || 1) * 100,
      snap =
        config.snap === false ? (v) => v : gsap.utils.snap(config.snap || 1), // some browsers shift by a pixel to accommodate flex layouts, so for example if width is 20% the first element's width might be 242px, and the next 243px, alternating back and forth. So we snap to 5 percentage points to make things look more natural
      totalWidth,
      curX,
      distanceToStart,
      distanceToLoop,
      item,
      i;
    gsap.set(items, {
      // convert "x" to "xPercent" to make things responsive, and populate the widths/xPercents Arrays to make lookups faster.
      xPercent: (i, el) => {
        let w = (widths[i] = parseFloat(gsap.getProperty(el, "width", "px")));
        xPercents[i] = snap(
          (parseFloat(gsap.getProperty(el, "x", "px")) / w) * 100 +
            gsap.getProperty(el, "xPercent")
        );
        return xPercents[i];
      },
    });
    gsap.set(items, { x: 0 });
    totalWidth =
      items[length - 1].offsetLeft +
      (xPercents[length - 1] / 100) * widths[length - 1] -
      startX +
      items[length - 1].offsetWidth *
        gsap.getProperty(items[length - 1], "scaleX") +
      (parseFloat(config.paddingRight) || 0);
    for (i = 0; i < length; i++) {
      item = items[i];
      curX = (xPercents[i] / 100) * widths[i];
      distanceToStart = item.offsetLeft + curX - startX;
      distanceToLoop =
        distanceToStart + widths[i] * gsap.getProperty(item, "scaleX");
      tl.to(
        item,
        {
          xPercent: snap(((curX - distanceToLoop) / widths[i]) * 100),
          duration: distanceToLoop / pixelsPerSecond,
        },
        0
      )
        .fromTo(
          item,
          {
            xPercent: snap(
              ((curX - distanceToLoop + totalWidth) / widths[i]) * 100
            ),
          },
          {
            xPercent: xPercents[i],
            duration:
              (curX - distanceToLoop + totalWidth - curX) / pixelsPerSecond,
            immediateRender: false,
          },
          distanceToLoop / pixelsPerSecond
        )
        .add("label" + i, distanceToStart / pixelsPerSecond);
      times[i] = distanceToStart / pixelsPerSecond;
    }
    function toIndex(index, vars) {
      vars = vars || {};
      Math.abs(index - curIndex) > length / 2 &&
        (index += index > curIndex ? -length : length); // always go in the shortest direction
      let newIndex = gsap.utils.wrap(0, length, index),
        time = times[newIndex];
      if (time > tl.time() !== index > curIndex) {
        // if we're wrapping the timeline's playhead, make the proper adjustments
        vars.modifiers = { time: gsap.utils.wrap(0, tl.duration()) };
        time += tl.duration() * (index > curIndex ? 1 : -1);
      }
      curIndex = newIndex;
      vars.overwrite = true;
      return tl.tweenTo(time, vars);
    }
    tl.next = (vars) => toIndex(curIndex + 1, vars);
    tl.previous = (vars) => toIndex(curIndex - 1, vars);
    tl.current = () => curIndex;
    tl.toIndex = (index, vars) => toIndex(index, vars);
    tl.times = times;
    tl.progress(1, true).progress(0, true); // pre-render for performance
    if (config.reversed) {
      tl.vars.onReverseComplete();
      tl.reverse();
    }
    return tl;
  }
});
</script>

<style scoped></style>
