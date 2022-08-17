<template>
  <div>
    <div class="page-head">
      <h3>Папки</h3>
      <p>Всего 9 папок</p>
    </div>
    <div class="folder-carousel">
      <VueSlickCarousel v-bind="settings">
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>120</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Неотсортированные
            </p>
          </div>
        </div>
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>150</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Получи 15 матер...
            </p>
          </div>
        </div>
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>150</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Первая страница
            </p>
          </div>
        </div>
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>150</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path class="path-head-folder-icon" d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Всегда с вами
            </p>
          </div>
        </div>
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>150</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Неотсортированные
            </p>
          </div>
        </div>
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>150</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Неотсортированные
            </p>
          </div>
        </div>
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>150</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Неотсортированные
            </p>
          </div>
        </div>
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>150</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Неотсортированные
            </p>
          </div>
        </div>
        <div>
          <div class="folder-carousel__item">
            <div class="d-flex justify-content-between pb-2">
              <span>150</span>
              <i>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <g clip-path="url(#clip0_3130_17473)">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 12.5C14 11.3954 13.1046 10.5 12 10.5C10.8954 10.5 10 11.3954 10 12.5C10 13.6046 10.8954 14.5 12 14.5C13.1046 14.5 14 13.6046 14 12.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 21.5C14 20.3954 13.1046 19.5 12 19.5C10.8954 19.5 10 20.3954 10 21.5C10 22.6046 10.8954 23.5 12 23.5C13.1046 23.5 14 22.6046 14 21.5Z" fill="#578FFC"/>
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14 3.5C14 2.39543 13.1046 1.5 12 1.5C10.8954 1.5 10 2.39543 10 3.5C10 4.60457 10.8954 5.5 12 5.5C13.1046 5.5 14 4.60457 14 3.5Z" fill="#578FFC"/>
                  </g>
                  <defs>
                    <clipPath id="clip0_3130_17473">
                      <rect width="24" height="24" fill="white"/>
                    </clipPath>
                  </defs>
                </svg>

              </i>
            </div>
            <div class="icon">
              <i>
                <svg width="50" height="50" viewBox="0 0 50 50" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M45.0626 13.8047H4.93738C2.20848 13.8209 0.00407453 16.0362 0.0013786 18.7652C-0.000459533 18.7929 -0.000459533 18.8208 0.0013786 18.8485L2.86886 40.2444C2.90367 42.9599 5.11359 45.1436 7.82937 45.1461H42.1902C44.9058 45.1436 47.1159 42.9599 47.1507 40.2444L49.9986 18.8485C50.0004 18.8208 50.0004 18.7929 49.9986 18.7652C49.996 16.0362 47.7916 13.8209 45.0626 13.8047Z" fill="url(#paint0_linear_3130_17485)"/>
                  <path d="M41.4009 8.86388H25.2842L22.0981 5.07488C21.9774 4.92979 21.7965 4.84842 21.6079 4.8543H8.59887C6.5697 4.857 4.9253 6.50139 4.92261 8.53057V12.0647H6.14803H45.0429C44.8043 10.2349 43.2462 8.8656 41.4009 8.86388Z" fill="#0057FF"/>
                  <defs>
                    <linearGradient id="paint0_linear_3130_17485" x1="25" y1="13.8047" x2="25" y2="45.1461" gradientUnits="userSpaceOnUse">
                      <stop stop-color="#0057FF" stop-opacity="0.8"/>
                      <stop offset="1" stop-color="#0057FF" stop-opacity="0.5"/>
                    </linearGradient>
                  </defs>
                </svg>

              </i>
            </div>
            <p>
              Неотсортированные
            </p>
          </div>
        </div>
        <template #nextArrow="arrowOption">
          <div class="custom-arrow">
            <i>
              <svg width="7" height="12" viewBox="0 0 7 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M0.840088 1.68005L5.52009 6.36005L0.840088 11.0401" stroke="url(#paint0_linear_3130_9086)" stroke-width="2"/>
                <defs>
                  <linearGradient id="paint0_linear_3130_9086" x1="0.840088" y1="1.68005" x2="6.93364" y2="3.26102" gradientUnits="userSpaceOnUse">
                    <stop stop-color="#1E212D"/>
                    <stop offset="0.0001" stop-color="#21273D"/>
                    <stop offset="1" stop-color="#1D202E"/>
                  </linearGradient>
                </defs>
              </svg>

            </i>
          </div>
        </template>
      </VueSlickCarousel>
    </div>
  </div>
</template>

<script>
export default {
  name: "FolderComponent",
  data () {
    return {
      settings: {
        centerMode: false,
        centerPadding: '20px',
        focusOnSelect: true,
        infinite: true,
        speed: 500,
        slidesToShow: 5,
      }
    }
  }
}
</script>

<style scoped>

</style>
