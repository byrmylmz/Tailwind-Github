<template>
  <div class="text-gray-900 text-sm">
    <!-- NAVBAR START -->
    <nav
      class="bg-gray-900 text-white px-4 py-3 flex items-center justify-between"
    >
      <div class="flex item-center space-x-4">
        <a href="" class="text-white hover:text-gray-400">
          <svg class="w-8 fill-current" viewBox="0 0 16 16" aria-hidden="true">
            <path
              fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
            ></path>
          </svg>
        </a>
        <div class="relative">
          <input
            type="text"
            class="rounded bg-gray-700 text-sm placeholder-white w-72 px-3 py-1"
            placeholder="Search or Jump to..."
          />
          <div class="absolute top-0 right-0 flex items-center h-full">
            <div
              class="
                border border-gray-600
                rounded
                tex-xs
                text-gray-400
                px-2
                mr-2
              "
            >
              /
            </div>
          </div>
        </div>
        <ul class="flex items-center font-semibold space-x-4">
          <li><a href="" class="hover:text-gray-400">Pull Request</a></li>
          <li><a href="" class="hover:text-gray-400">Pull Request</a></li>
          <li><a href="" class="hover:text-gray-400">Pull Request</a></li>
          <li><a href="" class="hover:text-gray-400">Pull Request</a></li>
        </ul>
      </div>

      <div class="flex items-center space-x-4 text-white">
        <a href="#" class="relative hover:text-gray-500">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
            />
          </svg>
          <div
            class="bg-blue-600 rounded-full w-2 h-2 absolute top-0 right-0"
          ></div>
        </a>
        <a href="#" class="flex items-center hover:text-gray-500">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 6v6m0 0v6m0-6h6m-6 0H6"
            />
          </svg>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-3"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </a>
        <a href="#" class="flex items-center hover:text-gray-500">
          <img
            src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4"
            alt="@byrmylmz"
            size="20"
            data-view-component="true"
            height="20"
            width="20"
            class="rounded-2xl"
          />
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-3 ml-1"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </a>
      </div>
    </nav>
    <!-- NAVBAR END -->
    <!-- repo start from here. -->
    <div class="repo-stats flex items-center justify-between px-8 py-4">
      <div class="flex">
        <svg
          class="w-4 fill-current text-gray-700"
          viewBox="0 0 16 16"
          aria-hidden="true"
        >
          <path
            fill-rule="evenodd"
            d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"
          ></path>
        </svg>
        <div class="flex items center text-xl ml-2">
          <a href="#" class="text-blue-600 hover:underline">TailwindCss</a>
          <span class="mx-2">/</span>
          <a href="#" class="text-blue-600 hover:underline font-semibold"
            >Bayram Yilmaz</a
          >
        </div>
      </div>
      <!-- left button items layout. -->
      <div class="flex space-x-3">
        <!-- watch button group flex -->
        <div class="flex text-xs">
          <!-- button in layout for watch -->
          <button
            class="
              border border-gray-400
              bg-gray-50
              hover:bg-gray-100
              rounded rounded-r-none
              px-3
              py-1
              flex
              items-center
              space-x-1
            "
          >
            <!-- eye svg for watch button -->
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-4"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
              />
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M2.458 12C3.732 7.943 7.523 5 12 5c4.478 0 8.268 2.943 9.542 7-1.274 4.057-5.064 7-9.542 7-4.477 0-8.268-2.943-9.542-7z"
              />
              <!-- down icon -->
            </svg>
            <div class="flex font-semibold">Watch</div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-3 ml-1"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M19 9l-7 7-7-7"
              />
            </svg>
            <!-- down icon end -->
          </button>
          <!-- watch button end -->
          <!-- second adjacent button - button group -->
          <button
            class="
              border border-gray-400 border-l-0
              rounded rounded-l-none
              px-3
              py-1
              font-semibold
              hover:text-blue-500
            "
          >
            430
          </button>
          <!-- button in layout for watch end -->
        </div>
        <!-- watch button group flex  end-->

        <!-- 
          Star button group flex
           -->
        <div class="flex text-xs">
          <!-- button in layout for watch -->
          <button
            class="
              bg-gray-50
              hover:bg-gray-100
              border border-gray-400
              rounded rounded-r-none
              px-3
              py-1
              flex
              items-center
              space-x-1
            "
          >
            <!-- star icon -->
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-4"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M11.049 2.927c.3-.921 1.603-.921 1.902 0l1.519 4.674a1 1 0 00.95.69h4.915c.969 0 1.371 1.24.588 1.81l-3.976 2.888a1 1 0 00-.363 1.118l1.518 4.674c.3.922-.755 1.688-1.538 1.118l-3.976-2.888a1 1 0 00-1.176 0l-3.976 2.888c-.783.57-1.838-.197-1.538-1.118l1.518-4.674a1 1 0 00-.363-1.118l-3.976-2.888c-.784-.57-.38-1.81.588-1.81h4.914a1 1 0 00.951-.69l1.519-4.674z"
              />
            </svg>
            <!-- star icon -->

            <div class="flex font-semibold">Star</div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-3 ml-1"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M19 9l-7 7-7-7"
              />
            </svg>
            <!-- down icon end -->
          </button>
          <!-- watch button end -->
          <!-- second adjacent button - button group -->
          <button
            class="
              border border-gray-400 border-l-0
              rounded rounded-l-none
              px-3
              py-1
              font-semibold
              hover:text-blue-500
            "
          >
            3
          </button>
          <!-- button in layout for watch end -->
        </div>
        <!-- watch button group flex  end-->
        <!-- watch button group flex -->
        <div class="flex text-xs">
          <!-- button in layout for watch -->
          <button
            class="
              bg-gray-50
              hover:bg-gray-100
              border border-gray-400
              rounded rounded-r-none
              px-3
              py-1
              flex
              items-center
              space-x-1
            "
          >
            <!-- eye svg for watch button -->
            <svg
              aria-hidden="true"
              viewBox="0 0 16 16"
              version="1.1"
              data-view-component="true"
              height="16"
              width="16"
              class="octicon octicon-repo-forked"
            >
              <path
                fill-rule="evenodd"
                d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"
              ></path>
            </svg>
            <div class="flex font-semibold">Fork</div>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="w-3 ml-1"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M19 9l-7 7-7-7"
              />
            </svg>
            <!-- down icon end -->
          </button>
          <!-- watch button end -->
          <!-- second adjacent button - button group -->
          <button
            class="
              border border-gray-400 border-l-0
              rounded rounded-l-none
              px-3
              py-1
              font-semibold
              hover:text-blue-700
            "
          >
            5
          </button>
          <!-- button in layout for watch end -->
        </div>
        <!-- watch button group flex  end-->
      </div>
    </div>
    <!-- unordered list for the .... -->
    <ul class="repo-nav border-b border-gray-200 flex items-center px-8 mt-4">
      <!-- list code item -->
      <li class="font-semibold">
        <a
          href="#"
          class="flex items-center border-b-2 border-red-500 px-4 pb-3"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
            />
          </svg>
          <span class="ml-2">Code</span>
        </a>
      </li>
      <!-- list code item end -->

      <!-- list issues item -->
      <li class="font-semibold">
        <a
          href="#"
          class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="w-5"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
            />
          </svg>
          <span class="ml-2">Issues</span>
          <div class="text-xs rounded bg-gray-200 px-2 ml-1">20</div>
        </a>
      </li>
           <!-- list issues item end -->
    </ul>
    <!-- unordered list for the .... -->
  </div>
</template>

<script>
export default {};
</script>
