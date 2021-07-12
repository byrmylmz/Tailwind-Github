<template>
  <div class="text-gray-900 text-sm">
    <!-- NAVBAR START -->
    <nav
      class="bg-gray-900 text-white px-4 py-4 flex items-center justify-between"
    >
      <div class="flex item-center space-x-4 px-5">
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
            class="
              rounded
              ring-1 ring-gray-600
              bg-gray-800
              text-sm
              placeholder-gray-300
              w-72
              px-3
              py-1
            "
            placeholder="Search or Jump to..."
          />
          <div class="absolute top-2 right-2 flex items-center">
            <div
              class="
                ring-1 ring-gray-500
                rounded
                text-xs text-gray-400
                px-1
                py-0
              "
            >
              /
            </div>
          </div>
        </div>
        <ul class="flex items-center font-semibold space-x-4">
          <li><a href="" class="hover:text-gray-400">Pull Request</a></li>
          <li><a href="" class="hover:text-gray-400">Issues</a></li>
          <li><a href="" class="hover:text-gray-400">Market Place</a></li>
          <li><a href="" class="hover:text-gray-400">Explore</a></li>
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
          class="
            flex
            items-center
            border-b-2 border-transparent
            hover:border-gray-200
            transition
            ease-in-out
            duration-150
            px-4
            pb-3
          "
        >
          <svg
            class="
              octicon octicon-issue-opened
              UnderlineNav-octicon
              d-none d-sm-inline
            "
            viewBox="0 0 16 16"
            version="1.1"
            width="16"
            height="16"
            aria-hidden="true"
          >
            <path d="M8 9.5a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
            <path
              fill-rule="evenodd"
              d="M8 0a8 8 0 100 16A8 8 0 008 0zM1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0z"
            ></path>
          </svg>
          <span class="ml-2">Issues</span>
          <div class="text-xs rounded bg-gray-200 px-2 ml-1">20</div>
        </a>
      </li>
      <!-- list issues item end -->
      <!-- list pull request item -->
      <li class="font-semibold">
        <a
          href="#"
          class="
            flex
            items-center
            border-b-2 border-transparent
            hover:border-gray-200
            transition
            ease-in-out
            duration-150
            px-4
            pb-3
          "
        >
          <svg
            class="
              octicon octicon-git-pull-request
              UnderlineNav-octicon
              d-none d-sm-inline
            "
            viewBox="0 0 16 16"
            version="1.1"
            width="16"
            height="16"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"
            ></path>
          </svg>
          <span class="ml-2">Issues</span>
          <div class="text-xs rounded bg-gray-200 px-2 ml-1">20</div>
        </a>
      </li>
      <!-- list pull request item end -->
    </ul>
    <!-- end repo nav .... -->
    <div class="container mx-auto my-8 px-4 flex ">
      <div class="file-explorer-container w-3/4 mr-8">
        <div class="branch-navigation flex items-center justify-between">
          <div class="flex items-center space-x-3">
            <button
              class="
                rounded-md
                border border-gray-300
                px-4
                py-1
                flex
                items-center
                space-x-2
                bg-gray-50
                hover:bg-gray-100
              "
            >
              <svg
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
                height="16"
                width="16"
                class="octicon octicon-git-branch text-gray"
              >
                <path
                  fill-rule="evenodd"
                  d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                ></path>
              </svg>
              <div class="flex font-semibold">Master</div>
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
            </button>
             <!-- branch  link -->
            <a href="#" class="flex items-center space-x-1 px-3 py-1 group">
              <svg
                class=" fill-current group-hover:text-blue-600"
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
                height="16"
                width="16"
                
              >
                <path
                  fill-rule="evenodd"
                  d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                ></path>
              </svg>
              <span class="group-hover:text-blue-600">
                <span class="font-semibold">25</span>
                <span class="text-gray-500 group-hover:text-blue-600">branches</span>
              </span>
            </a>
             <!-- branch  link -->
             <!-- span  link  start-->

            <a href="" class="flex items-center space-x-1 px-3 py-1 group">
              <svg
                aria-hidden="true"
                viewBox="0 0 16 16"
                version="1.1"
                data-view-component="true"
                height="16"
                width="16"
                class=" fill-current group-hover:text-blue-600"
              >
                <path
                  fill-rule="evenodd"
                  d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"
                ></path>
              </svg>
              <span class="group-hover:text-blue-600">
                <span class="font-semibold">45</span>
                <span class="text-gray-500 group-hover:text-blue-600">tags</span> 
                </span>
            </a>
            <!-- span link end -->
          </div>
          <!-- branch navigation right side -->
          <div class="flex items-center space-x-3">
            <button
              class="
                flex
                items-center
                font-semibold
                border
                rounded-md
                px-4
                py-1
                bg-gray-50
                hover:bg-gray-100
              "
            >
              Go to file
            </button>
            <button
              class="
                flex
                items-center
                font-semibold
                border
                rounded-md
                px-4
                py-1
                bg-gray-50
                hover:bg-gray-100
              "
            >
              Add file
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
            </button>
            <button
              class="
                flex
                items-center
                font-semibold
                border
                rounded-md
                px-4
                py-1
                bg-green-1
                text-white
                hover:bg-green-2
              "
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-4 mr-1"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"
                />
              </svg>
              Code
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
            </button>
          </div>
        </div>
        <!-- branch navigation -->

           <!-- 
             * commits container 
             -->
        <div class="commits-container bg-gray-100 rounded-md rounded-b-none border border-gray-300 flex items center justify-between px-4 py-4 mt-5">
          <div class="flex items-center space-x-2">
            <img  class="rounded-full w-6" src="https://avatars.githubusercontent.com/u/68708205?s=48&v=4" alt="">
            <a href="#" class="font-semibold hover:underline">byrmylmz</a>
            <a href="#" class="hover:underline hover:text-blue-600">Companies Crud Api</a>
          </div>
          <div class="flex items-center">
            <a href="#" class="font-mono text-gray-600  hover:text-blue-500 ml-2 hover:underline text-xs">4k44ki</a>
            <a href="#" class="hover:underline  text-gray-600 hover:text-blue-500 ml-2">3 Days ago</a>
            <a href="#" class="flex items-center space-x-1 px-3 py-1 group">
              <svg xmlns="http://www.w3.org/2000/svg" class="group-hover:text-blue-600 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
              </svg>
              <span class="group-hover:text-blue-600">
                <span class="font-semibold">25</span>
                <span class="text-gray-500 group-hover:text-blue-600">commits</span>
              </span>
            </a>
          </div>
        </div><!-- commits container end -->

        <!-- FILE EXPOLORER TABLE LINE START -->
        <div class="file=explorer rounded-md rounded-t-none border border-gray-300 text-gray-700 border-t-0 divide-y divide-gray-200">
          <!-- col 1 start -->
          <div class="flex items-center justify-between px-4 py-2 hover:bg-gray-100">
            <div class="flex items-center w-4/12">
              <svg  viewBox="0 0 16 16"  class="w-5 fill-current text-blue-400 flex items-center ">
                  <path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path>
              </svg>     
             <a href="#" class="hover:text-blue-500 ml-2 hover:underline">one</a>
            </div>
            <div class="w-6/12 truncate">Update issues template</div>
            <div class="w-2/12 text-right">11 days ago</div>
          </div>
          <!-- col 1 end -->
          <!-- col 1 start -->
          <div class="flex items-center justify-between px-4 py-2 hover:bg-gray-100">
            <div class="flex items-center w-4/12">
              <svg  viewBox="0 0 16 16"  class="w-5 fill-current text-blue-400 flex items-center ">
                  <path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path>
              </svg>     
             <a href="#" class="hover:text-blue-500 ml-2 hover:underline">one</a>
            </div>
            <div class="w-6/12 truncate">Update issues template</div>
            <div class="w-2/12 text-right">11 days ago</div>
          </div>
          <!-- col 1 end -->
            <!-- col 1 start -->
            <div class="flex items-center justify-between px-4 py-2 hover:bg-gray-100">
              <div class="flex items-center w-4/12">
                <svg  viewBox="0 0 16 16"  class="w-5 fill-current text-blue-400 flex items-center ">
                    <path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path>
                </svg>     
              <a href="#" class="hover:text-blue-500 ml-2 hover:underline">one</a>
              </div>
              <div class="w-6/12 truncate">Update issues template</div>
              <div class="w-2/12 text-right">11 days ago</div>
            </div>
            <!-- col 1 end -->
            <!-- blank ıtem col  -->
            <div class="flex items-center justify-between px-4 py-2 hover:bg-gray-100">
              <div class="flex items-center w-4/12">
                <svg aria-label="File" aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-file color-icon-tertiary">
                    <path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path>
                </svg>    
              <a href="#" class="hover:text-blue-500 ml-2 hover:underline">one</a>
              </div>
              <div class="w-6/12 truncate">Update issues template</div>
              <div class="w-2/12 text-right">11 days ago</div>
            </div>
            <!-- blank ıtem col  -->
            <!-- blank ıtem col  -->
            <div class="flex items-center justify-between px-4 py-2 hover:bg-gray-100">
              <div class="flex items-center w-4/12">
                <svg aria-label="File" aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-file color-icon-tertiary">
                    <path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path>
                </svg>    
              <a href="#" class="hover:text-blue-500 ml-2 hover:underline">one</a>
              </div>
              <div class="w-6/12 truncate">Update issues template</div>
              <div class="w-2/12 text-right">11 days ago</div>
            </div>
            <!-- blank ıtem col  -->
            <!-- blank ıtem col  -->
            <div class="flex items-center justify-between px-4 py-2 hover:bg-gray-100">
              <div class="flex items-center w-4/12">
                <svg aria-label="File" aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-file color-icon-tertiary">
                    <path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path>
                </svg>    
              <a href="#" class="hover:text-blue-500 ml-2 hover:underline">one</a>
              </div>
              <div class="w-6/12 truncate">Update issues template</div>
              <div class="w-2/12 text-right">11 days ago</div>
            </div>
            <!-- blank ıtem col  -->
            <!-- blank ıtem col  -->
            <div class="flex items-center justify-between px-4 py-2 hover:bg-gray-100">
              <div class="flex items-center w-4/12">
                <svg aria-label="File" aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-file color-icon-tertiary">
                    <path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path>
                </svg>    
              <a href="#" class="hover:text-blue-500 ml-2 hover:underline">one</a>
              </div>
              <div class="w-6/12 truncate">Update issues template</div>
              <div class="w-2/12 text-right">11 days ago</div>
            </div>
            <!-- blank ıtem col  -->
        </div> <!--end file-exploerer-container  -->
         <!-- readme layout title -->
           <div class="flex items-center justify-between rounded-md border border-gray-200 mt-4 p-1 rounded-b-none">
             <button class="rounded-md p-2 m-1 hover:bg-gray-100">
               <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" class="w-4">
                  <path fill-rule="evenodd" d="M2 4a1 1 0 100-2 1 1 0 000 2zm3.75-1.5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zm0 5a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5zM3 8a1 1 0 11-2 0 1 1 0 012 0zm-1 6a1 1 0 100-2 1 1 0 000 2z"></path>
              </svg>
             </button>
             <a href=""></a>
             <button class="rounded-md p-2 m-1 hover:bg-gray-100">
              <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true"  class="w-4">
                  <path fill-rule="evenodd" d="M11.013 1.427a1.75 1.75 0 012.474 0l1.086 1.086a1.75 1.75 0 010 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 01-.927-.928l.929-3.25a1.75 1.75 0 01.445-.758l8.61-8.61zm1.414 1.06a.25.25 0 00-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 000-.354l-1.086-1.086zM11.189 6.25L9.75 4.81l-6.286 6.287a.25.25 0 00-.064.108l-.558 1.953 1.953-.558a.249.249 0 00.108-.064l6.286-6.286z"></path>
              </svg>
             </button>
           </div>
          <!-- readme layout title --> 
      </div>

      <div class="sidebar w-1/4">
       <div class="about">
         <h4 class="text-base font-semibold">About</h4>
         <p class="text-base mt-4">A utility-first CSS framework for rapid UI development.</p>
         <!-- tailwindcss.com -->
         <div class="flex items-center space-x-2 mt-4">
            <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="16" width="16" class="octicon octicon-link flex-shrink-0 mr-2">
                <path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path>
            </svg>
           <a href="#" class="text-blue-600 hover:underline font-semibold">tailwindcss.com/</a>
         </div>
         <!-- tailwindcss.com -->
         <!-- tags -->
         <div class="tags tex-sm font-semibold flex items-center flex-wrap mt-2">
           <a href="#" class="bg-blue-100 hover:bg-blue-200 rounded-full px-2 py-1 mt-2 mr-2 text-blue-600 text-xs">tailwind</a>
           <a href="#" class="bg-blue-100 hover:bg-blue-200 rounded-full px-2 py-1 mt-2 mr-2 text-blue-600 text-xs">tailwind</a>
           <a href="#" class="bg-blue-100 hover:bg-blue-200 rounded-full px-2 py-1 mt-2 mr-2 text-blue-600 text-xs">tailwind</a>
           <a href="#" class="bg-blue-100 hover:bg-blue-200 rounded-full px-2 py-1 mt-2 mr-2 text-blue-600 text-xs">tailwind</a>
           <a href="#" class="bg-blue-100 hover:bg-blue-200 rounded-full px-2 py-1 mt-2 mr-2 text-blue-600 text-xs">tailwind</a>
           <a href="#" class="bg-blue-100 hover:bg-blue-200 rounded-full px-2 py-1 mt-2 mr-2 text-blue-600 text-xs">tailwind</a>
         </div>
         <!-- tags -->
         <!-- readme MIT licence -->
          <a href="#" class="flex items-center space-x-2 mt-4 group">
            <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1"  class=" w-4 fill-current group-hover:text-blue-600">
                <path fill-rule="evenodd" d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"></path>
            </svg>
            <span class="text-gray-600 group-hover:text-blue-600">Readme</span>
          </a>
          <a href="#" class="flex items-center space-x-2 mt-4 group">
             <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1"  class=" w-4 fill-current group-hover:text-blue-600">
                <path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"></path>
            </svg>
            <span class="text-gray-600 group-hover:text-blue-600">MIT Licence </span>
          </a>
       </div>
          <!-- releases -->
            <div class="releases border-t border-gray-00 mt-6 pt-6">
                <h4 class="text-base font-semibold flex items-center">
                  <span>Releases</span>
                  <div class="text-xs rounded-lg bg-gray-200 px-2 ml-1 ">59</div>
                </h4>
                <a href="#" class="items-start flex mt-4 group">
                    <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true " class="w-4 fill-current text-green-500 group-hover:text-blue-500 mt-1">
                        <path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"></path>
                    </svg>
                  <span class="ml-2">
                    <span class="font-semibold group-hover:text-blue-600">V1.5.6</span>
                      <span class="ml-1 text-xs border border-green-500 text-green-600 rounded-full font-semibold inline-block px-2">Latest</span>
                      <span class="block text-xs group-hover:text-blue-600">6 days ago</span>
                  </span>
                </a>
                <div class="mt-3">
                  <a href="#" class="text-xs text-blue-600 hover:underline">+ 157 releases</a>
                </div>
            </div>
          <!-- releases -->
          <!-- packages -->
            <div class="releases border-t border-gray-00 mt-6 pt-6">
                <h4 class="text-base font-semibold flex items-center">
                  <span>Packages</span>
                  <!-- <div class="text-xs rounded-lg bg-gray-200 px-2 ml-1 ">59</div> -->
                </h4>
                <div class="mt-2 text-xm text-gray-600">No packages published</div>
            </div>
          <!-- packages -->
          <!-- Used by -->
            <div class="releases border-t border-gray-00 mt-6 pt-6">
                <h4 class="text-base font-semibold flex items-center">
                  <span>Used by</span>
                  <div class="text-xs rounded-lg bg-gray-200 px-2 ml-1 ">243k</div>
                </h4>
                <div class="mt-4 flex items-center">
                  <a href="#" class="flex items-center -space-x-3">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                  </a>
                  <a href="#" class="text-blue-700 hover:underline text-xs font-semibold ml-2">+ 243,253</a>
                </div>
            </div>
          <!-- Used by -->
          <!-- Contributors -->
            <div class="releases border-t border-gray-00 mt-6 pt-6">
                <h4 class="text-base font-semibold flex items-center">
                  <span>Constributors</span>
                  <div class="text-xs rounded-lg bg-gray-200 px-2 ml-1 ">183</div>
                </h4>
                <div class="mt-4  ">
                    <a href="#" class="flex flex-wrap items-center ">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                    <img src="https://avatars.githubusercontent.com/u/68708205?s=60&amp;v=4" alt="avatar" class="w-9 border-2 border-white rounded-full">
                  </a>
                  <a href="#" class="block text-xs text-blue-500 hover:underline mt-3 font-semibold">+104 Contributors</a>
                </div>
            </div>
          <!-- Contributors -->
          <!-- Languages -->
            <div class="releases border-t border-gray-00 mt-6 pt-6">
                <h4 class="text-base font-semibold flex items-center">
                  <span>Languages</span>
                  <!-- <div class="text-xs rounded-lg bg-gray-200 px-2 ml-1 ">59</div> -->
                </h4>
                <div class="mt-4 flex">
                  <div class="w-5/12 h-2 rounded-md rounded-r-none bg-yellow-400"></div>
                  <div class="w-2/12 h-2 rounded-md rounded-r-none rounded-l-none bg-red-400"></div>
                  <div class="w-1/12 h-2 rounded-md rounded-r-none rounded-l-none bg-green-400"></div>
                  <div class="w-4/12 h-2 rounded-md rounded-l-none bg-blue-400"></div>
                </div>
                <div class=" mt-1 items-center inline-block ">
                  <div class="rounded-full bg-yellow-400 h-2 w-2  inline-block"></div>
                  <a href="#" class="inline-block font-semibold ml-1 text-sm  ">Javascript %50</a>
                </div>
                <div class=" mt-1 items-center inline-block ml-2">
                  <div class="rounded-full bg-red-400 h-2 w-2  inline-block"></div>
                  <a href="#" class="inline-block font-semibold ml-1 text-sm ">PHP %20</a>
                </div>
                <div class=" mt-1 items-center inline-block ml-2">
                  <div class="rounded-full bg-green-400 h-2 w-2  inline-block"></div>
                  <a href="#" class="inline-block font-semibold ml-1 text-sm ">HTML %20</a>
                </div>
                <div class=" mt-1 items-center">
                  <div class="rounded-full bg-blue-400 h-2 w-2  inline-block"></div>
                  <a href="#" class="inline-block font-semibold ml-1 text-sm ">Other %20</a>
                </div>
            </div>
          <!-- Languages -->

      </div>
    </div>
     <!-- readme MIT licence -->
    <!-- footer -->
     <footer class="container mx-auto border-t text-sm border-gray-400 py-10 flex items-center justify-between ">
       <!-- footer left list -->
       <ul class="flex items-center space-x-12">
         <li>2020 Github, Inc</li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
       </ul>
       <!-- footer left list -->
       <!-- footer github logo -->
       <div class="space-x-3 text-gray-400 fill-current hover:text-gray-00">
        <svg aria-hidden="true" viewBox="0 0 16 16" version="1.1" data-view-component="true" height="24" width="24" class="octicon octicon-mark-github">
            <path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path>
        </svg>
       </div>
       <!-- footer github logo -->
       <!-- footer right list -->
       <ul class="flex items-center space-x-12">
         <li><a href="#" class="text-blue-600 hover:underline">Contact Github</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
         <li><a href="#" class="text-blue-600 hover:underline">Terms</a></li>
       </ul>
       <!-- footer right list -->
     </footer>
  </div>
  
</template>

<script>
export default {};
</script>
