<template>
  <div>
    <LazyEditionsEHeader
      edition="1st"
      firsttitle="Issued certificates to participant"
      firstnote="Our first edition had people in different countries in Africa, which we successfully transitioned them into the tech space and issued participants that finished with a certificate of attendance."
      secondtitle="Partnership sponsorship with Clickpay"
      secondnote="The partnership between the Tech for Africa Bootcamp and ClickPay was a significant collaboration that had a positive impact on the bootcamp's participants."
      thirdtitle="Registered  over 1,000 beneficiaries in  Africa"
      thirdnote="Our first edition had people in different countries in Africa, which we successfully transitioned them into the tech space and issued participants that finished with a certificate of attendance."
      fourthtitle="Featured on Vanguard news"
      fourthnote="TFA is set to become the largest and most impactful bootcamp in Africa, aiming to train over 200,000 Africans within a span of two years.To learn more about the Tech for Africa Bootcamp and our mission for this transformative event, visit Vanguard News."
    />
    <LazyEditionsERatings
      courses="5"
      beneficiaries="1k +"
      duration="2 weeks"
      countries="10+"
    />
    <LazyEditionsEPictures edition="1st" />
    <LazyEditionsEReviews edition="1st" title="first" />
    <div class="editionsSponsors">
      <div class="btnb flex justify-center">
        <div class="btn outerbtn">
          <button class="titlebtn text-sm md:text-xl">
            Sponsorship & Incentives
          </button>
        </div>
      </div>

      <div class="editions bg-btnblue px-7 xl:px-[120px] py-4 md:py-0 mt-12">
        <div class="sponsortitle text-center xl:px-60 md:py-16 sm:pb-16">
          <div
            class="text-drkblue sm:text-[32px] text-[1.25rem] py-[1.5rem] sm:pt-[3.44rem] sm:pb-[0.75rem] sm:py-0 font-semibold"
          >
            Partners Who Made It Possible
          </div>
          <p class="text-semiblk sm:text-base md:px-24 text-sm hidden md:block">
            We extend our heartfelt gratitude to the partners and sponsors who
            believed in our mission and supported us during our first edition
          </p>
          <p
            class="text-semiblk sm:text-base text-sm sm:px-20 block lg:hidden font-normal leading-[1.3125rem] sm:leading-[1.3125rem] px-4 pb-[1.25rem]"
          >
            Here’s what some of our participants had to say about their
            transformative experiences at the first bootcamp
          </p>
        </div>
        <div class="bigbox bg-white p-3 md:p-5">
          <div class="editionboxes bg-btnblue p-5 lg:px-72 flex flex-col gap-3">
            <div class="redicon">
              <img
                src="../../assets/images/icons/redglobe.svg"
                alt=""
                class=""
              />
            </div>
            <div class="edition-name font-semibold">
              1st bootcamp - Official sponsor of this edition.
            </div>
            <div class="imgcontainer flex gap-3 items-center">
              <div class="sponsor flex gap-5 items-center">
                <img src="../../assets/images/icons/clickpay.svg" alt="" />
              </div>
            </div>
            <div
              class="summery text-semiblk text-xs md:text-base hidden lg:block lg:pb-[1.75rem]"
            >
              We partnered with Clickpay to bring the first edition of the
              bootcamp to live. Tech for Africa Bootcamp by Axia Africa" provide
              individuals with first-hand knowledge and practical skills
              necessary to kickstart their
            </div>
            <div
              class="summery text-semiblk text-xs md:text-base block lg:hidden pb-[1rem]"
            >
              The partnership between the Tech for Africa Bootcamp and ClickPay
              was a significant collaboration that had a positive impact on the
              bootcamp's participants. ClickPay, a payment processing platform,
              played a vital role in supporting the bootcamp and enhancing the
              learning experience for participants.
            </div>

            <div class="bootimg bg-axiablue w-full px-8 h-[140px] md:h-[319px]">
              <img
                src="../../assets/images/homepage/bootcamp.png"
                alt=""
                class="h-full w-full object-cover"
              />
            </div>
            <!-- <div class="see">
              <a
                href=""
                class="flex items-center gap-2 text-axiared underline text-sm md:text-base"
              >
                See more
                <span
                  ><img
                    src="../../assets/images/icons/arrowright.svg"
                    alt=""
                    class=""
                /></span>
              </a>
            </div> -->
          </div>
        </div>
        <div class="waitlist bg-white px-5 pb-5 pt-8">
          <div class="waitlistbox bg-btnblue">
            <div class="p-5 flex justify-center">
              <div
                class="waitlistinfo max-w-[614px] text-center flex flex-col gap-5"
              >
                <div
                  class="join text-base md:text-[28px] font-semibold px-[68px] sm:leading-[2.625rem]"
                >
                  Become a Partner sponsor of our next bootcamp
                </div>
                <p class="hello px-16 md:px-8 text-sm md:text-base">
                  Tech for Africa Bootcamp by Axia Africa" provide individuals
                  with first-hand knowledge and practical skills necessary to
                  kickstart their journey in the tech industry.
                </p>
                <form action="" class="flex flex-col gap-3 px-14">
                  <input
                    type="text"
                    name=""
                    id=""
                    placeholder="Axiaafrica@gmail.com"
                    class="sm:px-5 px-12 py-4 rounded-lg placeholder:text-sm md:placeholder:text-base"
                  />
                  <div class="btn mt-3">
                    <button class="bluebtn text-sm md:text-base">
                      Reach out to us
                    </button>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="mentors mt-24">
      <div class="w-full flex justify-center container-center">
        <div
          class="borderbox flex justify-center items-center gap-6 px-5 py-3 border-[1px] border-[#F3F2F0] text-2xl"
        >
          <button class="active text-sm sm:text-base">
            1st edition mentors
          </button>
        </div>
      </div>

      <div class="gallerybox mt-6 bg-litpink py-16 px-3">
        <div
          class="mentorbox container-center grid grid-cols-4 gap-y-20 gap-x-4"
        >
          <div
            class="mentor w-full flex flex-col gap-1"
            v-for="mentor in Edition1"
            :key="mentor.id"
          >
            <div class="picture w-[300px] md:w-full h-[300px]">
              <img
                :src="mentor.picture"
                alt=""
                class="w-full h-full object-cover"
              />
            </div>
            <div class="mentorname text-lg font-bold">
              {{ mentor.mentorname }}
            </div>
            <div class="mentorname">{{ mentor.job }}</div>
            <a
              :href="mentor.socialUrl"
              target="_blank"
              class="socials flex gap-3 items-center"
            >
              <div class="icon">
                <img :src="mentor.socialicon" alt="" class="" />
              </div>
              <div class="handle text-lg underline">
                {{ mentor.socialhandle }}
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
    <LazyLandingBlog />
  </div>
</template>

<script setup>
import { Edition1 } from "@/components/editions/editionData";
definePageMeta({
  layout: "default",
});
</script>

<style scoped></style>
