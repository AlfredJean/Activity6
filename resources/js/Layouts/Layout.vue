<template>
  <div class="flex">
    <div
      class="flex flex-col w-64 h-screen py-8 bg-white border-r dark:bg-gray-800 dark:border-gray-600"
    >
     
      <h2
        class="text-3xl font-semibold text-center text-gray-800 dark:text-white"
      >
        AlfredJean
      </h2>

      <div class="flex flex-col items-center mt-6 -mx-2">
        <img
          class="object-cover w-24 h-24 mx-2 rounded-full"
          src="https://lh3.googleusercontent.com/-JaE3OxCuGys/YF4o5XOFurI/AAAAAAAAARo/BcYwMfWMLV0-NIGlqKehkDwAPEH7a0rdQCEwYBhgLKtQDAL1OcqwZEQkcU7YdgnX6MUaJU9JkkjIFL8EIDSLPuSWWsgbHcE9vpdeXUetyUA48r40P8-Vra7Oet1y0k8IcoQAQtOPEqZnS0SYG-Wpm7_pdTVyZMPRD21ZX3I5Ym3z6P-yMQwRMhw9TZl24_gUq_W3HKnPgi_cMzv0dQNFnS84dyLFUtQODiWcE0RPXBOg4I2m6PmeqxgIxwYDOJbIxUb7dOcJBEAZx118-0L8x-INNjzHP69JYD9Lu4bDt5x5bVDD_hOfnecl59wuuTxCd8ecoXb6QvWaQgJQ3cLwNyVpztTMmHdYE9Vur38rXTUf2Xw63U0tv1bL93oknkFCQ7XkXaQjvIVhpJpTzaplvEfnKhDtTiPQmiMkfC2fkGPr2jvqelpw1x5_UqkNeMGrwVqNrIZ9kEQvs7AhDD4vcwk-71pQ9Ck5KzRysPRlbzNJcJV1lWLseoEDq7__QkzNmrbAa5V-mBN1NTFPun9NSoZE7G2-vwoQGaQJELGlSL7VmgQ6IGAwqixeWZ3dF-lBSzoz9NOAhhT82KuxRiDP-b6p7YRXeuu8MhMDfUgOgf5KiQ9ybIcg4-ng9W64vD5u8YUs37zltTJixR2fiFfcVCEv0dmvuMNjW-IIG/w139-h140-p/resumeImage.jpg"
          alt="avatar"
        />
        <h4
          class="mx-2 mt-2 font-medium text-gray-800 dark:text-gray-200 hover:underline"
        >
          Alfred Jean Micua
        </h4>
        <p
          class="mx-2 mt-1 text-sm font-medium text-gray-600 dark:text-gray-400 hover:underline"
        >
          alfredjean.micua@lorma.edu
        </p>
      </div>

      <div class="flex flex-col justify-between flex-1 mt-6">
        <nav>
          <a
            class="flex items-center px-4 py-2 text-gray-700 bg-gray-200 dark:bg-gray-700 dark:text-gray-200"
            href="#"
          >
            <svg
              class="w-5 h-5"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M19 11H5M19 11C20.1046 11 21 11.8954 21 13V19C21 20.1046 20.1046 21 19 21H5C3.89543 21 3 20.1046 3 19V13C3 11.8954 3.89543 11 5 11M19 11V9C19 7.89543 18.1046 7 17 7M5 11V9C5 7.89543 5.89543 7 7 7M7 7V5C7 3.89543 7.89543 3 9 3H15C16.1046 3 17 3.89543 17 5V7M7 7H17"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>

            <span class="mx-4 font-medium">Dashboard</span>
          </a>

          <a
            class="flex items-center px-4 py-2 mt-5 text-gray-600 transition-colors duration-200 transform dark:text-gray-400 hover:bg-gray-200 dark:hover:bg-gray-700 dark:hover:text-gray-200 hover:text-gray-700"
            href="#"
          >
            <svg
              class="w-5 h-5"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M16 7C16 9.20914 14.2091 11 12 11C9.79086 11 8 9.20914 8 7C8 4.79086 9.79086 3 12 3C14.2091 3 16 4.79086 16 7Z"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M12 14C8.13401 14 5 17.134 5 21H19C19 17.134 15.866 14 12 14Z"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>

            <span class="mx-4 font-medium">Accounts</span>
          </a>

          <a
            class="flex items-center px-4 py-2 mt-5 text-gray-600 transition-colors duration-200 transform dark:text-gray-400 hover:bg-gray-200 dark:hover:bg-gray-700 dark:hover:text-gray-200 hover:text-gray-700"
            href="#"
          >
            <svg
              class="w-5 h-5"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M15 5V7M15 11V13M15 17V19M5 5C3.89543 5 3 5.89543 3 7V10C4.10457 10 5 10.8954 5 12C5 13.1046 4.10457 14 3 14V17C3 18.1046 3.89543 19 5 19H19C20.1046 19 21 18.1046 21 17V14C19.8954 14 19 13.1046 19 12C19 10.8954 19.8954 10 21 10V7C21 5.89543 20.1046 5 19 5H5Z"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>

            <span class="mx-4 font-medium">Tickets</span>
          </a>

          <a
            class="flex items-center px-4 py-2 mt-5 text-gray-600 transition-colors duration-200 transform dark:text-gray-400 hover:bg-gray-200 dark:hover:bg-gray-700 dark:hover:text-gray-200 hover:text-gray-700"
            href="#"
          >
            <svg
              class="w-5 h-5"
              viewBox="0 0 24 24"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10.3246 4.31731C10.751 2.5609 13.249 2.5609 13.6754 4.31731C13.9508 5.45193 15.2507 5.99038 16.2478 5.38285C17.7913 4.44239 19.5576 6.2087 18.6172 7.75218C18.0096 8.74925 18.5481 10.0492 19.6827 10.3246C21.4391 10.751 21.4391 13.249 19.6827 13.6754C18.5481 13.9508 18.0096 15.2507 18.6172 16.2478C19.5576 17.7913 17.7913 19.5576 16.2478 18.6172C15.2507 18.0096 13.9508 18.5481 13.6754 19.6827C13.249 21.4391 10.751 21.4391 10.3246 19.6827C10.0492 18.5481 8.74926 18.0096 7.75219 18.6172C6.2087 19.5576 4.44239 17.7913 5.38285 16.2478C5.99038 15.2507 5.45193 13.9508 4.31731 13.6754C2.5609 13.249 2.5609 10.751 4.31731 10.3246C5.45193 10.0492 5.99037 8.74926 5.38285 7.75218C4.44239 6.2087 6.2087 4.44239 7.75219 5.38285C8.74926 5.99037 10.0492 5.45193 10.3246 4.31731Z"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9C13.6569 9 15 10.3431 15 12Z"
                stroke="currentColor"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </svg>

            <span class="mx-4 font-medium">Settings</span>
          </a>
        </nav>
      </div>
    </div>
    <div class="w-full bg-gray-50 flex flex-col">
      <div>
        <div class="w-full bg-yellow-500">
          <nav class="bg-white shadow dark:bg-gray-800">
            <div class="container px-6 py-3 mx-auto">
              <div class="md:flex md:items-center md:justify-between">
                <div class="flex items-center justify-between">
                  <div class="text-xl font-semibold text-gray-700">
                    <a
                      class="text-xl font-bold text-gray-800 dark:text-white md:text-2xl hover:text-gray-700 dark:hover:text-gray-300"
                      href="#"
                      >AlfredJean</a
                    >
                  </div>

                  <!-- Mobile menu button -->
                  <div class="flex md:hidden">
                    <button
                      type="button"
                      class="text-gray-500 dark:text-gray-200 hover:text-gray-600 dark:hover:text-gray-400 focus:outline-none focus:text-gray-600 dark:focus:text-gray-400"
                      aria-label="toggle menu"
                    >
                      <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                        <path
                          fill-rule="evenodd"
                          d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                        ></path>
                      </svg>
                    </button>
                  </div>
                </div>

                <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
                <div class="flex-1 md:flex md:items-center md:justify-between">
                  <div
                    class="flex flex-col -mx-4 md:flex-row md:items-center md:mx-8"
                  >
                    <a
                      href="#"
                      class="px-2 py-1 mx-2 mt-2 text-sm font-medium text-gray-700 transition-colors duration-200 transform rounded-md md:mt-0 dark:text-gray-200 hover:bg-gray-300 dark:hover:bg-gray-700"
                      >JOIN NOW</a
                    >
                    <a
                      href="#"
                      class="px-2 py-1 mx-2 mt-2 text-sm font-medium text-gray-700 transition-colors duration-200 transform rounded-md md:mt-0 dark:text-gray-200 hover:bg-gray-300 dark:hover:bg-gray-700"
                      >Browse Articles</a
                    >
                    <a
                      href="#"
                      class="px-2 py-1 mx-2 mt-2 text-sm font-medium text-gray-700 transition-colors duration-200 transform rounded-md md:mt-0 dark:text-gray-200 hover:bg-gray-300 dark:hover:bg-gray-700"
                      >Random Items</a
                    >
                    <a
                      href="#"
                      class="px-2 py-1 mx-2 mt-2 text-sm font-medium text-gray-700 transition-colors duration-200 transform rounded-md md:mt-0 dark:text-gray-200 hover:bg-gray-300 dark:hover:bg-gray-700"
                      >Experts</a
                    >
                  </div>

                  <div class="flex items-center mt-4 md:mt-0">
                    <button
                      class="hidden mx-4 text-gray-600 md:block dark:text-gray-200 hover:text-gray-700 dark:hover:text-gray-400 focus:text-gray-700 dark:focus:text-gray-400 focus:outline-none"
                      aria-label="show notifications"
                    >
                      <svg
                        class="w-6 h-6"
                        viewBox="0 0 24 24"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          d="M15 17H20L18.5951 15.5951C18.2141 15.2141 18 14.6973 18 14.1585V11C18 8.38757 16.3304 6.16509 14 5.34142V5C14 3.89543 13.1046 3 12 3C10.8954 3 10 3.89543 10 5V5.34142C7.66962 6.16509 6 8.38757 6 11V14.1585C6 14.6973 5.78595 15.2141 5.40493 15.5951L4 17H9M15 17V18C15 19.6569 13.6569 21 12 21C10.3431 21 9 19.6569 9 18V17M15 17H9"
                          stroke="currentColor"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                      </svg>
                    </button>

                    <button
                      type="button"
                      class="flex items-center focus:outline-none"
                      aria-label="toggle profile dropdown"
                    >
                      <div
                        class="w-8 h-8 overflow-hidden border-2 border-gray-400 rounded-full"
                      >
                        <img
                          src="https://lh3.googleusercontent.com/-JaE3OxCuGys/YF4o5XOFurI/AAAAAAAAARo/BcYwMfWMLV0-NIGlqKehkDwAPEH7a0rdQCEwYBhgLKtQDAL1OcqwZEQkcU7YdgnX6MUaJU9JkkjIFL8EIDSLPuSWWsgbHcE9vpdeXUetyUA48r40P8-Vra7Oet1y0k8IcoQAQtOPEqZnS0SYG-Wpm7_pdTVyZMPRD21ZX3I5Ym3z6P-yMQwRMhw9TZl24_gUq_W3HKnPgi_cMzv0dQNFnS84dyLFUtQODiWcE0RPXBOg4I2m6PmeqxgIxwYDOJbIxUb7dOcJBEAZx118-0L8x-INNjzHP69JYD9Lu4bDt5x5bVDD_hOfnecl59wuuTxCd8ecoXb6QvWaQgJQ3cLwNyVpztTMmHdYE9Vur38rXTUf2Xw63U0tv1bL93oknkFCQ7XkXaQjvIVhpJpTzaplvEfnKhDtTiPQmiMkfC2fkGPr2jvqelpw1x5_UqkNeMGrwVqNrIZ9kEQvs7AhDD4vcwk-71pQ9Ck5KzRysPRlbzNJcJV1lWLseoEDq7__QkzNmrbAa5V-mBN1NTFPun9NSoZE7G2-vwoQGaQJELGlSL7VmgQ6IGAwqixeWZ3dF-lBSzoz9NOAhhT82KuxRiDP-b6p7YRXeuu8MhMDfUgOgf5KiQ9ybIcg4-ng9W64vD5u8YUs37zltTJixR2fiFfcVCEv0dmvuMNjW-IIG/w139-h140-p/resumeImage.jpg"
                          class="object-cover w-full h-full"
                          alt="avatar"
                        />
                      </div>

                      <h3
                        class="mx-2 text-sm font-medium text-gray-700 dark:text-gray-200 md:hidden"
                      >
                        Alfred Jean Micua
                      </h3>
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </nav>
        </div>

        <div class="w-full bg-gray-50 h-full">
          <div class="m-20">
            <div
              class="max-w-xs mx-auto overflow-hidden bg-white rounded-lg shadow-lg dark:bg-gray-800"
            >
              <div class="px-4 py-2">
                <h1
                  class="text-3xl font-bold text-gray-800 uppercase dark:text-white"
                >
                  Logitech G Pro X Wireless Gaming Mouse
                </h1>
                <p class="mt-1 text-sm text-gray-600 dark:text-gray-400">
                  Our lightest PRO mouse yet, PRO X SUPERLIGHT is an engineering
                  breakthrough achieving a weight of less than 63 grams—nearly
                  25% lighter than our standard PRO Wireless mouse. This was
                  accomplished through meticulous engineering to produce extreme
                  weight reduction with zero compromises to performance.
                </p>
              </div>

              <img
                class="object-cover w-full h-48 mt-2"
                src="https://vamers-com.exactdn.com/wp-content/uploads/2018/08/Vamers-Technology-Logitech-launches-G-Pro-Wireless-Mouse-02.jpg"
                alt="Logitech G Pro X Wireless Gaming Mouse"
              />

              <div
                class="flex items-center justify-between px-4 py-2 bg-gray-900"
              >
                <h1 class="text-lg font-bold text-white">$150</h1>
                <button
                  class="px-2 py-1 text-xs font-semibold text-gray-900 uppercase transition-colors duration-200 transform bg-white rounded hover:bg-gray-200 focus:bg-gray-400 focus:outline-none"
                >
                  Add to cart
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>