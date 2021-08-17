<template>
    <div>
        <div class=" my-3 text-center text-red-600 font-black text-2xl">
            APPLY FOR HNG INTERN'S MENTOR
        </div>
    <div class="rounded-md sm:mx-72 mt-10 bg-gray-100 shadow-100">
      <img src="@/assets/hng.png" class="w-full rounded-lg -mt-5" alt="" />
      <div class="p-10">
        <!-- Name -->
        <div class="grid sm:grid-cols-2 gap-4 mb-3">
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">First Name</label>
            <input
              type="text"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="First Name"
            />
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Last Name</label>
            <input
              type="text"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="Last Name"
            />
          </div>
        </div>

        <!-- Gender and Nationality -->

        <div class="grid sm:grid-cols-2 gap-4 mb-3">
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Gender</label>
            <div
              class="
                rounded-lg
                text-xl
                p-3
                bg-white
                flex
                items-center
                outline-none
                border-2 border-blue-300
                space-x-5
              "
            >
              <div>
                <input type="radio" class="-1 mr-3" />
                <span>Male</span>
              </div>
              <div>
                <input type="radio" class="-1 mr-3" />
                <span>Female</span>
              </div>
            </div>
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Nationality</label>
            <select
              class="
                rounded-lg
                p-3
                bg-white
                outline-none
                border-2 border-blue-300
              "
            >
              <option>Nigeria</option>
              <option>Others</option>
            </select>
          </div>
        </div>

        <!-- home address -->
        <div class="space-y-2 flex flex-col mb-3">
          <label class="text-xl text-blue-700">Address</label>

          <textarea
            class="rounded-lg p-3 outline-none border-2 border-blue-300"
          ></textarea>
        </div>

        <!-- Birth Date -->
        <div class="grid sm:grid-cols-3 gap-4 mb-3">
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Day</label>
            <select
              class="
                rounded-lg
                p-3
                bg-white
                outline-none
                border-2 border-blue-300
              "
            >
              <option>Sunday</option>
              <option>Monday</option>
              <option>Tuesday</option>
              <option>Wednesday</option>
              <option>Thursday</option>
              <option>Friday</option>
            </select>
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Month</label>
            <select
              class="
                rounded-lg
                p-3
                bg-white
                outline-none
                border-2 border-blue-300
              "
            >
              <option>Jan</option>
              <option>Feb</option>
              <option>March</option>
              <option>April</option>
              <option>May</option>
              <option>June</option>
            </select>
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Year</label>
            <select
              class="
                rounded-lg
                p-3
                bg-white
                outline-none
                border-2 border-blue-300
              "
            >
              <option>2000</option>
              <option>2001</option>
              <option>2002</option>
              <option>2003</option>
              <option>2004</option>
              <option>2005</option>
            </select>
          </div>
        </div>

        <!-- Area of Specialization -->
        <div class="grid sm:grid-cols-2 gap-4 mb-3">
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Area of Specialization</label>
            <select
              class="
                rounded-lg
                p-3
                bg-white
                outline-none
                border-2 border-blue-300
              "
            >
              <option>Frontend Developer</option>
              <option>Backend Developer</option>
              <option>UI/UX</option>
              <option>Project Management</option>
            </select>
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Years of Experience</label>
            <input
              type="text"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="Years"
            />
          </div>
        </div>

        <!-- place of work  -->
        <div class="grid sm:grid-cols-2 gap-4 mb-3">
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Place of Work</label>
            <input
              type="text"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="Organization"
            />
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Current Position</label>
            <input
              type="text"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="Position"
            />
          </div>
        </div>

        <!-- email Address  -->
        <div class="grid sm:grid-cols-2 gap-4 mb-3">
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Email Address</label>
            <input
              type="email"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="jane.doe@gmail.com"
            />
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Phone Number</label>
            <input
              type="text"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="telephone"
            />
          </div>
        </div>

        <!-- Repository -->
         <div class="grid sm:grid-cols-2 gap-4 mb-3">
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Github Account</label>
            <input
              type="text"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="github repo"
            />
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">LinkedIn Account</label>
            <input
              type="text"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="linkedIn"
            />
          </div>
        </div>

        <!-- Upload resume And Cover letter -->
        
         <div class="grid grid gap-4 mb-3">
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Upload Resume</label>
            <input
              type="file"
              class="rounded-lg p-3 outline-none border-2 border-blue-300"
              placeholder="First Name"
            />
          </div>
          <div class="space-y-2 flex flex-col">
            <label class="text-xl text-blue-700">Cover Letter</label>
            <textarea
            class="rounded-lg p-3 outline-none border-2 border-blue-300"
          ></textarea>
          </div>
        </div>


        <button class='rounded-lg flex justify-center items-center py-3 bg-blue-500 w-full text-white'>Apply</button>
      
      </div>
    </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>