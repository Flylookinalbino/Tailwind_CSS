# LAYOUT
## Container
>   container	None	width: 100%;
>               sm (640px)	max-width: 640px;
>               md (768px)	max-width: 768px;
>               lg (1024px)	max-width: 1024px;
>               xl (1280px)	max-width: 1280px;

## Display
>   block	            display: block;
>   inline-block	    display: inline-block;
>   inline	            display: inline;
>   flex	            display: flex;
>   inline-flex	        display: inline-flex;
>   table	            display: table;
>   table-caption	    display: table-caption;
>   table-cell	        display: table-cell;
>   table-column	    display: table-column;
>   table-column-group	display: table-column-group;
>   table-footer-group	display: table-footer-group;
>   table-header-group	display: table-header-group;
>   table-row-group	    display: table-row-group;
>   table-row	        display: table-row;
>   flow-root	        display: flow-root;
>   grid	            display: grid;
>   inline-grid	        display: inline-grid;
>   contents	        display: contents;
>   hidden	            display: none;

## Floats
>   float-right	float: right;
>   float-left	float: left;
>   float-none	float: none;
>   clearfix	&::after {
>               content: "";
>               display: table;
>               clear: both;
>               }

## Clear
>   clear-left	clear: left;
>   clear-right	clear: right;
>   clear-both	clear: both;
>   clear-none	clear: none;

## Object Fit
>   object-contain	    object-fit: contain;
>   object-cover	    object-fit: cover;
>   object-fill	        object-fit: fill;
>   object-none	        object-fit: none;
>   object-scale-down	object-fit: scale-down;

## Object Position
>   object-bottom	object-position: bottom;
>   object-center	object-position: center;
>   object-left	object-position: left;
>   object-left-bottom	object-position: left bottom;
>   object-left-top	object-position: left top;
>   object-right	object-position: right;
>   object-right-bottom	object-position: right bottom;
>   object-right-top	object-position: right top;
>   object-top	object-position: top;

## Position
>   static	position: static;
>   fixed	position: fixed;
>   absolute	position: absolute;
>   relative	position: relative;
>   sticky	position: sticky;

## Top / Right / Bottom / Left
>   inset-0	top: 0;
>           right: 0;
>           bottom: 0;
>           left: 0;
>   inset-auto	top: auto;
>           right: auto;
>           bottom: auto;
>           left: auto;
>   inset-y-0	top: 0;
>           bottom: 0;
>   inset-x-0	right: 0;
>           left: 0;
>   inset-y-auto	top: auto;
>           bottom: auto;
>   inset-x-auto	right: auto;
>           left: auto;
>   top-0	top: 0;
>   right-0	right: 0;
>   bottom-0	bottom: 0;
>   left-0	left: 0;
>   top-auto	top: auto;
>   right-auto	right: auto;
>   bottom-auto	bottom: auto;
>   left-auto	left: auto;

## Visibility
>   visible	visibility: visible;
>   invisible	visibility: hidden;

## Z-Index
>   z-0	    z-index: 0;
>   z-10	z-index: 10;
>   z-20	z-index: 20;
>   z-30	z-index: 30;
>   z-40	z-index: 40;
>   z-50	z-index: 50;
>   z-auto	z-index: auto;

# BACKGROUNDS
## Background Attachment
>   bg-fixed	background-attachment: fixed;
>   bg-local	background-attachment: local;
>   bg-scroll	background-attachment: scroll;

## Background Clip
>   bg-clip-border	background-clip: border-box;
>   bg-clip-padding	background-clip: padding-box;
>   bg-clip-content	background-clip: content-box;
>   bg-clip-text	background-clip: text;

## Background Color
>   bg-transparent	background-color: transparent;	
>   bg-current	    background-color: currentColor;	
>   bg-black	    background-color: #000;	
>   bg-white	    background-color: #fff;	
>   bg-gray-100	    background-color: #f7fafc;	
>   bg-gray-200	    background-color: #edf2f7;	
>   bg-gray-300	    background-color: #e2e8f0;	
>   bg-gray-400	    background-color: #cbd5e0;	
>   bg-gray-500	    background-color: #a0aec0;	
>   bg-gray-600	    background-color: #718096;	
>   bg-gray-700	    background-color: #4a5568;	
>   bg-gray-800	    background-color: #2d3748;	
>   bg-gray-900	    background-color: #1a202c;	
>   bg-red-100	    background-color: #fff5f5;	
>   bg-red-200	    background-color: #fed7d7;	
>   bg-red-300	    background-color: #feb2b2;	
>   bg-red-400	    background-color: #fc8181;	
>   bg-red-500	    background-color: #f56565;	
>   bg-red-600	    background-color: #e53e3e;	
>   bg-red-700	    background-color: #c53030;	
>   bg-red-800	    background-color: #9b2c2c;	
>   bg-red-900	    background-color: #742a2a;	
>   bg-orange-100	background-color: #fffaf0;	
>   bg-orange-200	background-color: #feebc8;	
>   bg-orange-300	background-color: #fbd38d;	
>   bg-orange-400	background-color: #f6ad55;	
>   bg-orange-500	background-color: #ed8936;	
>   bg-orange-600	background-color: #dd6b20;	
>   bg-orange-700	background-color: #c05621;	
>   bg-orange-800	background-color: #9c4221;	
>   bg-orange-900	background-color: #7b341e;	
>   bg-yellow-100	background-color: #fffff0;	
>   bg-yellow-200	background-color: #fefcbf;	
>   bg-yellow-300	background-color: #faf089;	
>   bg-yellow-400	background-color: #f6e05e;	
>   bg-yellow-500	background-color: #ecc94b;	
>   bg-yellow-600	background-color: #d69e2e;	
>   bg-yellow-700	background-color: #b7791f;	
>   bg-yellow-800	background-color: #975a16;	
>   bg-yellow-900	background-color: #744210;	
>   bg-green-100	background-color: #f0fff4;	
>   bg-green-200	background-color: #c6f6d5;	
>   bg-green-300	background-color: #9ae6b4;	
>   bg-green-400	background-color: #68d391;	
>   bg-green-500	background-color: #48bb78;	
>   bg-green-600	background-color: #38a169;	
>   bg-green-700	background-color: #2f855a;	
>   bg-green-800	background-color: #276749;	
>   bg-green-900	background-color: #22543d;	
>   bg-teal-100	background-color: #e6fffa;	
>   bg-teal-200	background-color: #b2f5ea;	
>   bg-teal-300	background-color: #81e6d9;	
>   bg-teal-400	background-color: #4fd1c5;	
>   bg-teal-500	background-color: #38b2ac;	
>   bg-teal-600	background-color: #319795;	
>   bg-teal-700	background-color: #2c7a7b;	
>   bg-teal-800	background-color: #285e61;	
>   bg-teal-900	background-color: #234e52;	
>   bg-blue-100	background-color: #ebf8ff;	
>   bg-blue-200	background-color: #bee3f8;	
>   bg-blue-300	background-color: #90cdf4;	
>   bg-blue-400	background-color: #63b3ed;	
>   bg-blue-500	background-color: #4299e1;	
>   bg-blue-600	background-color: #3182ce;	
>   bg-blue-700	background-color: #2b6cb0;	
>   bg-blue-800	background-color: #2c5282;	
>   bg-blue-900	background-color: #2a4365;	
>   bg-indigo-100	background-color: #ebf4ff;	
>   bg-indigo-200	background-color: #c3dafe;	
>   bg-indigo-300	background-color: #a3bffa;	
>   bg-indigo-400	background-color: #7f9cf5;	
>   bg-indigo-500	background-color: #667eea;	
>   bg-indigo-600	background-color: #5a67d8;	
>   bg-indigo-700	background-color: #4c51bf;	
>   bg-indigo-800	background-color: #434190;	
>   bg-indigo-900	background-color: #3c366b;	
>   bg-purple-100	background-color: #faf5ff;	
>   bg-purple-200	background-color: #e9d8fd;	
>   bg-purple-300	background-color: #d6bcfa;	
>   bg-purple-400	background-color: #b794f4;	
>   bg-purple-500	background-color: #9f7aea;	
>   bg-purple-600	background-color: #805ad5;	
>   bg-purple-700	background-color: #6b46c1;	
>   bg-purple-800	background-color: #553c9a;	
>   bg-purple-900	background-color: #44337a;	
>   bg-pink-100	background-color: #fff5f7;	
>   bg-pink-200	background-color: #fed7e2;	
>   bg-pink-300	background-color: #fbb6ce;	
>   bg-pink-400	background-color: #f687b3;	
>   bg-pink-500	background-color: #ed64a6;	
>   bg-pink-600	background-color: #d53f8c;	
>   bg-pink-700	background-color: #b83280;	
>   bg-pink-800	background-color: #97266d;	
>   bg-pink-900	background-color: #702459;

## Background Opacity
>   bg-opacity-0	--bg-opacity: 0;
>   bg-opacity-25	--bg-opacity: 0.25;
>   bg-opacity-50	--bg-opacity: 0.5;
>   bg-opacity-75	--bg-opacity: 0.75;
>   bg-opacity-100	--bg-opacity: 1;

## Background Position
>   bg-bottom	background-position: bottom;
>   bg-center	background-position: center;
>   bg-left	background-position: left;
>   bg-left-bottom	background-position: left bottom;
>   bg-left-top	background-position: left top;
>   bg-right	background-position: right;
>   bg-right-bottom	background-position: right bottom;
>   bg-right-top	background-position: right top;
>   bg-top	background-position: top;

## Background Repeat
>   bg-repeat	background-repeat: repeat;
>   bg-no-repeat	background-repeat: no-repeat;
>   bg-repeat-x	background-repeat: repeat-x;
>   bg-repeat-y	background-repeat: repeat-y;
>   bg-repeat-round	background-repeat: round;
>   bg-repeat-space	background-repeat: space;

## Background Size
>   bg-auto	background-size: auto;
>   bg-cover	background-size: cover;
>   bg-contain	background-size: contain;

## Background Image
>   bg-none	background-image: none;
>   bg-gradient-to-t	background-image: linear-gradient(to top, var(--gradient-color-stops));
>   bg-gradient-to-tr	background-image: linear-gradient(to top right, var(--gradient-color-stops));
>   bg-gradient-to-r	background-image: linear-gradient(to right, var(--gradient-color-stops));
>   bg-gradient-to-br	background-image: linear-gradient(to bottom right, var(--gradient-color-stops));
>   bg-gradient-to-b	background-image: linear-gradient(to bottom, var(--gradient-color-stops));
>   bg-gradient-to-bl	background-image: linear-gradient(to bottom left, var(--gradient-color-stops));
>   bg-gradient-to-l	background-image: linear-gradient(to left, var(--gradient-color-stops));
>   bg-gradient-to-tl	background-image: linear-gradient(to top left, var(--gradient-color-stops));

## Gradient Color Stops
>   from-transparent	--gradient-from-color: transparent;	
>   from-current	--gradient-from-color: currentColor;	
>   from-black	--gradient-from-color: #000;	
>   from-white	--gradient-from-color: #fff;	
>   from-gray-100	--gradient-from-color: #f7fafc;	
>   from-gray-200	--gradient-from-color: #edf2f7;	
>   from-gray-300	--gradient-from-color: #e2e8f0;	
>   from-gray-400	--gradient-from-color: #cbd5e0;	
>   from-gray-500	--gradient-from-color: #a0aec0;	
>   from-gray-600	--gradient-from-color: #718096;	
>   from-gray-700	--gradient-from-color: #4a5568;	
>   from-gray-800	--gradient-from-color: #2d3748;	
>   from-gray-900	--gradient-from-color: #1a202c;	
>   from-red-100	--gradient-from-color: #fff5f5;	
>   from-red-200	--gradient-from-color: #fed7d7;	
>   from-red-300	--gradient-from-color: #feb2b2;	
>   from-red-400	--gradient-from-color: #fc8181;	
>   from-red-500	--gradient-from-color: #f56565;	
>   from-red-600	--gradient-from-color: #e53e3e;	
>   from-red-700	--gradient-from-color: #c53030;	
>   from-red-800	--gradient-from-color: #9b2c2c;	
>   from-red-900	--gradient-from-color: #742a2a;	
>   from-orange-100	--gradient-from-color: #fffaf0;	
>   from-orange-200	--gradient-from-color: #feebc8;	
>   from-orange-300	--gradient-from-color: #fbd38d;	
>   from-orange-400	--gradient-from-color: #f6ad55;	
>   from-orange-500	--gradient-from-color: #ed8936;	
>   from-orange-600	--gradient-from-color: #dd6b20;	
>   from-orange-700	--gradient-from-color: #c05621;	
>   from-orange-800	--gradient-from-color: #9c4221;	
>   from-orange-900	--gradient-from-color: #7b341e;	
>   from-yellow-100	--gradient-from-color: #fffff0;	
>   from-yellow-200	--gradient-from-color: #fefcbf;	
>   from-yellow-300	--gradient-from-color: #faf089;	
>   from-yellow-400	--gradient-from-color: #f6e05e;	
>   from-yellow-500	--gradient-from-color: #ecc94b;	
>   from-yellow-600	--gradient-from-color: #d69e2e;	
>   from-yellow-700	--gradient-from-color: #b7791f;	
>   from-yellow-800	--gradient-from-color: #975a16;	
>   from-yellow-900	--gradient-from-color: #744210;	
>   from-green-100	--gradient-from-color: #f0fff4;	
>   from-green-200	--gradient-from-color: #c6f6d5;	
>   from-green-300	--gradient-from-color: #9ae6b4;	
>   from-green-400	--gradient-from-color: #68d391;	
>   from-green-500	--gradient-from-color: #48bb78;	
>   from-green-600	--gradient-from-color: #38a169;	
>   from-green-700	--gradient-from-color: #2f855a;	
>   from-green-800	--gradient-from-color: #276749;	
>   from-green-900	--gradient-from-color: #22543d;	
>   from-teal-100	--gradient-from-color: #e6fffa;	
>   from-teal-200	--gradient-from-color: #b2f5ea;	
>   from-teal-300	--gradient-from-color: #81e6d9;	
>   from-teal-400	--gradient-from-color: #4fd1c5;	
>   from-teal-500	--gradient-from-color: #38b2ac;	
>   from-teal-600	--gradient-from-color: #319795;	
>   from-teal-700	--gradient-from-color: #2c7a7b;	
>   from-teal-800	--gradient-from-color: #285e61;	
>   from-teal-900	--gradient-from-color: #234e52;	
>   from-blue-100	--gradient-from-color: #ebf8ff;	
>   from-blue-200	--gradient-from-color: #bee3f8;	
>   from-blue-300	--gradient-from-color: #90cdf4;	
>   from-blue-400	--gradient-from-color: #63b3ed;	
>   from-blue-500	--gradient-from-color: #4299e1;	
>   from-blue-600	--gradient-from-color: #3182ce;	
>   from-blue-700	--gradient-from-color: #2b6cb0;	
>   from-blue-800	--gradient-from-color: #2c5282;	
>   from-blue-900	--gradient-from-color: #2a4365;	
>   from-indigo-100	--gradient-from-color: #ebf4ff;	
>   from-indigo-200	--gradient-from-color: #c3dafe;	
>   from-indigo-300	--gradient-from-color: #a3bffa;	
>   from-indigo-400	--gradient-from-color: #7f9cf5;	
>   from-indigo-500	--gradient-from-color: #667eea;	
>   from-indigo-600	--gradient-from-color: #5a67d8;	
>   from-indigo-700	--gradient-from-color: #4c51bf;	
>   from-indigo-800	--gradient-from-color: #434190;	
>   from-indigo-900	--gradient-from-color: #3c366b;	
>   from-purple-100	--gradient-from-color: #faf5ff;	
>   from-purple-200	--gradient-from-color: #e9d8fd;	
>   from-purple-300	--gradient-from-color: #d6bcfa;	
>   from-purple-400	--gradient-from-color: #b794f4;	
>   from-purple-500	--gradient-from-color: #9f7aea;	
>   from-purple-600	--gradient-from-color: #805ad5;	
>   from-purple-700	--gradient-from-color: #6b46c1;	
>   from-purple-800	--gradient-from-color: #553c9a;	
>   from-purple-900	--gradient-from-color: #44337a;	
>   from-pink-100	--gradient-from-color: #fff5f7;	
>   from-pink-200	--gradient-from-color: #fed7e2;	
>   from-pink-300	--gradient-from-color: #fbb6ce;	
>   from-pink-400	--gradient-from-color: #f687b3;	
>   from-pink-500	--gradient-from-color: #ed64a6;	
>   from-pink-600	--gradient-from-color: #d53f8c;	
>   from-pink-700	--gradient-from-color: #b83280;	
>   from-pink-800	--gradient-from-color: #97266d;	
>   from-pink-900	--gradient-from-color: #702459;	
>   via-transparent	--gradient-via-color: transparent;	
>   via-current	--gradient-via-color: currentColor;	
>   via-black	--gradient-via-color: #000;	
>   via-white	--gradient-via-color: #fff;	
>   via-gray-100	--gradient-via-color: #f7fafc;	
>   via-gray-200	--gradient-via-color: #edf2f7;	
>   via-gray-300	--gradient-via-color: #e2e8f0;	
>   via-gray-400	--gradient-via-color: #cbd5e0;	
>   via-gray-500	--gradient-via-color: #a0aec0;	
>   via-gray-600	--gradient-via-color: #718096;	
>   via-gray-700	--gradient-via-color: #4a5568;	
>   via-gray-800	--gradient-via-color: #2d3748;	
>   via-gray-900	--gradient-via-color: #1a202c;	
>   via-red-100	--gradient-via-color: #fff5f5;	
>   via-red-200	--gradient-via-color: #fed7d7;	
>   via-red-300	--gradient-via-color: #feb2b2;	
>   via-red-400	--gradient-via-color: #fc8181;	
>   via-red-500	--gradient-via-color: #f56565;	
>   via-red-600	--gradient-via-color: #e53e3e;	
>   via-red-700	--gradient-via-color: #c53030;	
>   via-red-800	--gradient-via-color: #9b2c2c;	
>   via-red-900	--gradient-via-color: #742a2a;	
>   via-orange-100	--gradient-via-color: #fffaf0;	
>   via-orange-200	--gradient-via-color: #feebc8;	
>   via-orange-300	--gradient-via-color: #fbd38d;	
>   via-orange-400	--gradient-via-color: #f6ad55;	
>   via-orange-500	--gradient-via-color: #ed8936;	
>   via-orange-600	--gradient-via-color: #dd6b20;	
>   via-orange-700	--gradient-via-color: #c05621;	
>   via-orange-800	--gradient-via-color: #9c4221;	
>   via-orange-900	--gradient-via-color: #7b341e;	
>   via-yellow-100	--gradient-via-color: #fffff0;	
>   via-yellow-200	--gradient-via-color: #fefcbf;	
>   via-yellow-300	--gradient-via-color: #faf089;	
>   via-yellow-400	--gradient-via-color: #f6e05e;	
>   via-yellow-500	--gradient-via-color: #ecc94b;	
>   via-yellow-600	--gradient-via-color: #d69e2e;	
>   via-yellow-700	--gradient-via-color: #b7791f;	
>   via-yellow-800	--gradient-via-color: #975a16;	
>   via-yellow-900	--gradient-via-color: #744210;	
>   via-green-100	--gradient-via-color: #f0fff4;	
>   via-green-200	--gradient-via-color: #c6f6d5;	
>   via-green-300	--gradient-via-color: #9ae6b4;	
>   via-green-400	--gradient-via-color: #68d391;	
>   via-green-500	--gradient-via-color: #48bb78;	
>   via-green-600	--gradient-via-color: #38a169;	
>   via-green-700	--gradient-via-color: #2f855a;	
>   via-green-800	--gradient-via-color: #276749;	
>   via-green-900	--gradient-via-color: #22543d;	
>   via-teal-100	--gradient-via-color: #e6fffa;	
>   via-teal-200	--gradient-via-color: #b2f5ea;	
>   via-teal-300	--gradient-via-color: #81e6d9;	
>   via-teal-400	--gradient-via-color: #4fd1c5;	
>   via-teal-500	--gradient-via-color: #38b2ac;	
>   via-teal-600	--gradient-via-color: #319795;	
>   via-teal-700	--gradient-via-color: #2c7a7b;	
>   via-teal-800	--gradient-via-color: #285e61;	
>   via-teal-900	--gradient-via-color: #234e52;	
>   via-blue-100	--gradient-via-color: #ebf8ff;	
>   via-blue-200	--gradient-via-color: #bee3f8;	
>   via-blue-300	--gradient-via-color: #90cdf4;	
>   via-blue-400	--gradient-via-color: #63b3ed;	
>   via-blue-500	--gradient-via-color: #4299e1;	
>   via-blue-600	--gradient-via-color: #3182ce;	
>   via-blue-700	--gradient-via-color: #2b6cb0;	
>   via-blue-800	--gradient-via-color: #2c5282;	
>   via-blue-900	--gradient-via-color: #2a4365;	
>   via-indigo-100	--gradient-via-color: #ebf4ff;	
>   via-indigo-200	--gradient-via-color: #c3dafe;	
>   via-indigo-300	--gradient-via-color: #a3bffa;	
>   via-indigo-400	--gradient-via-color: #7f9cf5;	
>   via-indigo-500	--gradient-via-color: #667eea;	
>   via-indigo-600	--gradient-via-color: #5a67d8;	
>   via-indigo-700	--gradient-via-color: #4c51bf;	
>   via-indigo-800	--gradient-via-color: #434190;	
>   via-indigo-900	--gradient-via-color: #3c366b;	
>   via-purple-100	--gradient-via-color: #faf5ff;	
>   via-purple-200	--gradient-via-color: #e9d8fd;	
>   via-purple-300	--gradient-via-color: #d6bcfa;	
>   via-purple-400	--gradient-via-color: #b794f4;	
>   via-purple-500	--gradient-via-color: #9f7aea;	
>   via-purple-600	--gradient-via-color: #805ad5;	
>   via-purple-700	--gradient-via-color: #6b46c1;	
>   via-purple-800	--gradient-via-color: #553c9a;	
>   via-purple-900	--gradient-via-color: #44337a;	
>   via-pink-100	--gradient-via-color: #fff5f7;	
>   via-pink-200	--gradient-via-color: #fed7e2;	
>   via-pink-300	--gradient-via-color: #fbb6ce;	
>   via-pink-400	--gradient-via-color: #f687b3;	
>   via-pink-500	--gradient-via-color: #ed64a6;	
>   via-pink-600	--gradient-via-color: #d53f8c;	
>   via-pink-700	--gradient-via-color: #b83280;	
>   via-pink-800	--gradient-via-color: #97266d;	
>   via-pink-900	--gradient-via-color: #702459;	
>   to-transparent	--gradient-to-color: transparent;	
>   to-current	--gradient-to-color: currentColor;	
>   to-black	--gradient-to-color: #000;	
>   to-white	--gradient-to-color: #fff;	
>   to-gray-100	--gradient-to-color: #f7fafc;	
>   to-gray-200	--gradient-to-color: #edf2f7;	
>   to-gray-300	--gradient-to-color: #e2e8f0;	
>   to-gray-400	--gradient-to-color: #cbd5e0;	
>   to-gray-500	--gradient-to-color: #a0aec0;	
>   to-gray-600	--gradient-to-color: #718096;	
>   to-gray-700	--gradient-to-color: #4a5568;	
>   to-gray-800	--gradient-to-color: #2d3748;	
>   to-gray-900	--gradient-to-color: #1a202c;	
>   to-red-100	--gradient-to-color: #fff5f5;	
>   to-red-200	--gradient-to-color: #fed7d7;	
>   to-red-300	--gradient-to-color: #feb2b2;	
>   to-red-400	--gradient-to-color: #fc8181;	
>   to-red-500	--gradient-to-color: #f56565;	
>   to-red-600	--gradient-to-color: #e53e3e;	
>   to-red-700	--gradient-to-color: #c53030;	
>   to-red-800	--gradient-to-color: #9b2c2c;	
>   to-red-900	--gradient-to-color: #742a2a;	
>   to-orange-100	--gradient-to-color: #fffaf0;	
>   to-orange-200	--gradient-to-color: #feebc8;	
>   to-orange-300	--gradient-to-color: #fbd38d;	
>   to-orange-400	--gradient-to-color: #f6ad55;	
>   to-orange-500	--gradient-to-color: #ed8936;	
>   to-orange-600	--gradient-to-color: #dd6b20;	
>   to-orange-700	--gradient-to-color: #c05621;	
>   to-orange-800	--gradient-to-color: #9c4221;	
>   to-orange-900	--gradient-to-color: #7b341e;	
>   to-yellow-100	--gradient-to-color: #fffff0;	
>   to-yellow-200	--gradient-to-color: #fefcbf;	
>   to-yellow-300	--gradient-to-color: #faf089;	
>   to-yellow-400	--gradient-to-color: #f6e05e;	
>   to-yellow-500	--gradient-to-color: #ecc94b;	
>   to-yellow-600	--gradient-to-color: #d69e2e;	
>   to-yellow-700	--gradient-to-color: #b7791f;	
>   to-yellow-800	--gradient-to-color: #975a16;	
>   to-yellow-900	--gradient-to-color: #744210;	
>   to-green-100	--gradient-to-color: #f0fff4;	
>   to-green-200	--gradient-to-color: #c6f6d5;	
>   to-green-300	--gradient-to-color: #9ae6b4;	
>   to-green-400	--gradient-to-color: #68d391;	
>   to-green-500	--gradient-to-color: #48bb78;	
>   to-green-600	--gradient-to-color: #38a169;	
>   to-green-700	--gradient-to-color: #2f855a;	
>   to-green-800	--gradient-to-color: #276749;	
>   to-green-900	--gradient-to-color: #22543d;	
>   to-teal-100	--gradient-to-color: #e6fffa;	
>   to-teal-200	--gradient-to-color: #b2f5ea;	
>   to-teal-300	--gradient-to-color: #81e6d9;	
>   to-teal-400	--gradient-to-color: #4fd1c5;	
>   to-teal-500	--gradient-to-color: #38b2ac;	
>   to-teal-600	--gradient-to-color: #319795;	
>   to-teal-700	--gradient-to-color: #2c7a7b;	
>   to-teal-800	--gradient-to-color: #285e61;	
>   to-teal-900	--gradient-to-color: #234e52;	
>   to-blue-100	--gradient-to-color: #ebf8ff;	
>   to-blue-200	--gradient-to-color: #bee3f8;	
>   to-blue-300	--gradient-to-color: #90cdf4;	
>   to-blue-400	--gradient-to-color: #63b3ed;	
>   to-blue-500	--gradient-to-color: #4299e1;	
>   to-blue-600	--gradient-to-color: #3182ce;	
>   to-blue-700	--gradient-to-color: #2b6cb0;	
>   to-blue-800	--gradient-to-color: #2c5282;	
>   to-blue-900	--gradient-to-color: #2a4365;	
>   to-indigo-100	--gradient-to-color: #ebf4ff;	
>   to-indigo-200	--gradient-to-color: #c3dafe;	
>   to-indigo-300	--gradient-to-color: #a3bffa;	
>   to-indigo-400	--gradient-to-color: #7f9cf5;	
>   to-indigo-500	--gradient-to-color: #667eea;	
>   to-indigo-600	--gradient-to-color: #5a67d8;	
>   to-indigo-700	--gradient-to-color: #4c51bf;	
>   to-indigo-800	--gradient-to-color: #434190;	
>   to-indigo-900	--gradient-to-color: #3c366b;	
>   to-purple-100	--gradient-to-color: #faf5ff;	
>   to-purple-200	--gradient-to-color: #e9d8fd;	
>   to-purple-300	--gradient-to-color: #d6bcfa;	
>   to-purple-400	--gradient-to-color: #b794f4;	
>   to-purple-500	--gradient-to-color: #9f7aea;	
>   to-purple-600	--gradient-to-color: #805ad5;	
>   to-purple-700	--gradient-to-color: #6b46c1;	
>   to-purple-800	--gradient-to-color: #553c9a;	
>   to-purple-900	--gradient-to-color: #44337a;	
>   to-pink-100	--gradient-to-color: #fff5f7;	
>   to-pink-200	--gradient-to-color: #fed7e2;	
>   to-pink-300	--gradient-to-color: #fbb6ce;	
>   to-pink-400	--gradient-to-color: #f687b3;	
>   to-pink-500	--gradient-to-color: #ed64a6;	
>   to-pink-600	--gradient-to-color: #d53f8c;	
>   to-pink-700	--gradient-to-color: #b83280;	
>   to-pink-800	--gradient-to-color: #97266d;	
>   to-pink-900	--gradient-to-color: #702459;

# BORDERS
## Border Radius
>   rounded-none	border-radius: 0;
>   rounded-sm	    border-radius: 0.125rem;
>   rounded	        border-radius: 0.25rem;
>   rounded-md  	border-radius: 0.375rem;
>   rounded-lg  	border-radius: 0.5rem;
>   rounded-full	border-radius: 9999px;
>   rounded-t-none	border-top-left-radius: 0;
>                   border-top-right-radius: 0;
>   rounded-r-none	border-top-right-radius: 0;
>                   border-bottom-right-radius: 0;
>   rounded-b-none	border-bottom-right-radius: 0;
>                   border-bottom-left-radius: 0;
>   rounded-l-none	border-top-left-radius: 0;
>                   border-bottom-left-radius: 0;
>   rounded-t-sm	border-top-left-radius: 0.125rem;
>                   border-top-right-radius: 0.125rem;
>   rounded-r-sm	border-top-right-radius: 0.125rem;
>                   border-bottom-right-radius: 0.125rem;
>   rounded-b-sm	border-bottom-right-radius: 0.125rem;
>                   border-bottom-left-radius: 0.125rem;
>   rounded-l-sm	border-top-left-radius: 0.125rem;
>                   border-bottom-left-radius: 0.125rem;
>   rounded-t	    border-top-left-radius: 0.25rem;
>                   border-top-right-radius: 0.25rem;
>   rounded-r	    border-top-right-radius: 0.25rem;
>                   border-bottom-right-radius: 0.25rem;
>   rounded-b	    border-bottom-right-radius: 0.25rem;
>                   border-bottom-left-radius: 0.25rem;
>   rounded-l	    border-top-left-radius: 0.25rem;
>                   border-bottom-left-radius: 0.25rem;
>   rounded-t-md	border-top-left-radius: 0.375rem;
>                   border-top-right-radius: 0.375rem;
>   rounded-r-md	border-top-right-radius: 0.375rem;
>                   border-bottom-right-radius: 0.375rem;
>   rounded-b-md	border-bottom-right-radius: 0.375rem;
>                   border-bottom-left-radius: 0.375rem;
>   rounded-l-md	border-top-left-radius: 0.375rem;
>                   border-bottom-left-radius: 0.375rem;
>   rounded-t-lg	border-top-left-radius: 0.5rem;
>                   border-top-right-radius: 0.5rem;
>   rounded-r-lg	border-top-right-radius: 0.5rem;
>                   border-bottom-right-radius: 0.5rem;
>   rounded-b-lg	border-bottom-right-radius: 0.5rem;
>                   border-bottom-left-radius: 0.5rem;
>   rounded-l-lg	border-top-left-radius: 0.5rem;
>                   border-bottom-left-radius: 0.5rem;
>   rounded-t-full	border-top-left-radius: 9999px;
>                   border-top-right-radius: 9999px;
>   rounded-r-full	border-top-right-radius: 9999px;
>                   border-bottom-right-radius: 9999px;
>   rounded-b-full	border-bottom-right-radius: 9999px;
>                   border-bottom-left-radius: 9999px;
>   rounded-l-full	border-top-left-radius: 9999px;
>                   border-bottom-left-radius: 9999px;
>   rounded-tl-none	border-top-left-radius: 0;
>   rounded-tr-none	border-top-right-radius: 0;
>   rounded-br-none	border-bottom-right-radius: 0;
>   rounded-bl-none	border-bottom-left-radius: 0;
>   rounded-tl-sm	border-top-left-radius: 0.125rem;
>   rounded-tr-sm	border-top-right-radius: 0.125rem;
>   rounded-br-sm	border-bottom-right-radius: 0.125rem;
>   rounded-bl-sm	border-bottom-left-radius: 0.125rem;
>   rounded-tl	    border-top-left-radius: 0.25rem;
>   rounded-tr	    border-top-right-radius: 0.25rem;
>   rounded-br	    border-bottom-right-radius: 0.25rem;
>   rounded-bl	    border-bottom-left-radius: 0.25rem;
>   rounded-tl-md	border-top-left-radius: 0.375rem;
>   rounded-tr-md	border-top-right-radius: 0.375rem;
>   rounded-br-md	border-bottom-right-radius: 0.375rem;
>   rounded-bl-md	border-bottom-left-radius: 0.375rem;
>   rounded-tl-lg	border-top-left-radius: 0.5rem;
>   rounded-tr-lg	border-top-right-radius: 0.5rem;
>   rounded-br-lg	border-bottom-right-radius: 0.5rem;
>   rounded-bl-lg	border-bottom-left-radius: 0.5rem;
>   rounded-tl-full	border-top-left-radius: 9999px;
>   rounded-tr-full	border-top-right-radius: 9999px;
>   rounded-br-full	border-bottom-right-radius: 9999px;
>   rounded-bl-full	border-bottom-left-radius: 9999px;

## Border Width
>   border-0	border-width: 0;
>   border-2	border-width: 2px;
>   border-4	border-width: 4px;
>   border-8	border-width: 8px;
>   border	border-width: 1px;
>   border-t-0	border-top-width: 0;
>   border-r-0	border-right-width: 0;
>   border-b-0	border-bottom-width: 0;
>   border-l-0	border-left-width: 0;
>   border-t-2	border-top-width: 2px;
>   border-r-2	border-right-width: 2px;
>   border-b-2	border-bottom-width: 2px;
>   border-l-2	border-left-width: 2px;
>   border-t-4	border-top-width: 4px;
>   border-r-4	border-right-width: 4px;
>   border-b-4	border-bottom-width: 4px;
>   border-l-4	border-left-width: 4px;
>   border-t-8	border-top-width: 8px;
>   border-r-8	border-right-width: 8px;
>   border-b-8	border-bottom-width: 8px;
>   border-l-8	border-left-width: 8px;
>   border-t	border-top-width: 1px;
>   border-r	border-right-width: 1px;
>   border-b	border-bottom-width: 1px;
>   border-l	border-left-width: 1px;

## Border Color
>   border-transparent	border-color: transparent;	
>   border-current	border-color: currentColor;	
>   border-black	border-color: #000;	
>   border-white	border-color: #fff;	
>   border-gray-100	border-color: #f7fafc;	
>   border-gray-200	border-color: #edf2f7;	
>   border-gray-300	border-color: #e2e8f0;	
>   border-gray-400	border-color: #cbd5e0;	
>   border-gray-500	border-color: #a0aec0;	
>   border-gray-600	border-color: #718096;	
>   border-gray-700	border-color: #4a5568;	
>   border-gray-800	border-color: #2d3748;	
>   border-gray-900	border-color: #1a202c;	
>   border-red-100	border-color: #fff5f5;	
>   border-red-200	border-color: #fed7d7;	
>   border-red-300	border-color: #feb2b2;	
>   border-red-400	border-color: #fc8181;	
>   border-red-500	border-color: #f56565;	
>   border-red-600	border-color: #e53e3e;	
>   border-red-700	border-color: #c53030;	
>   border-red-800	border-color: #9b2c2c;	
>   border-red-900	border-color: #742a2a;	
>   border-orange-100	border-color: #fffaf0;	
>   border-orange-200	border-color: #feebc8;	
>   border-orange-300	border-color: #fbd38d;	
>   border-orange-400	border-color: #f6ad55;	
>   border-orange-500	border-color: #ed8936;	
>   border-orange-600	border-color: #dd6b20;	
>   border-orange-700	border-color: #c05621;	
>   border-orange-800	border-color: #9c4221;	
>   border-orange-900	border-color: #7b341e;	
>   border-yellow-100	border-color: #fffff0;	
>   border-yellow-200	border-color: #fefcbf;	
>   border-yellow-300	border-color: #faf089;	
>   border-yellow-400	border-color: #f6e05e;	
>   border-yellow-500	border-color: #ecc94b;	
>   border-yellow-600	border-color: #d69e2e;	
>   border-yellow-700	border-color: #b7791f;	
>   border-yellow-800	border-color: #975a16;	
>   border-yellow-900	border-color: #744210;	
>   border-green-100	border-color: #f0fff4;	
>   border-green-200	border-color: #c6f6d5;	
>   border-green-300	border-color: #9ae6b4;	
>   border-green-400	border-color: #68d391;	
>   border-green-500	border-color: #48bb78;	
>   border-green-600	border-color: #38a169;	
>   border-green-700	border-color: #2f855a;	
>   border-green-800	border-color: #276749;	
>   border-green-900	border-color: #22543d;	
>   border-teal-100	border-color: #e6fffa;	
>   border-teal-200	border-color: #b2f5ea;	
>   border-teal-300	border-color: #81e6d9;	
>   border-teal-400	border-color: #4fd1c5;	
>   border-teal-500	border-color: #38b2ac;	
>   border-teal-600	border-color: #319795;	
>   border-teal-700	border-color: #2c7a7b;	
>   border-teal-800	border-color: #285e61;	
>   border-teal-900	border-color: #234e52;	
>   border-blue-100	border-color: #ebf8ff;	
>   border-blue-200	border-color: #bee3f8;	
>   border-blue-300	border-color: #90cdf4;	
>   border-blue-400	border-color: #63b3ed;	
>   border-blue-500	border-color: #4299e1;	
>   border-blue-600	border-color: #3182ce;	
>   border-blue-700	border-color: #2b6cb0;	
>   border-blue-800	border-color: #2c5282;	
>   border-blue-900	border-color: #2a4365;	
>   border-indigo-100	border-color: #ebf4ff;	
>   border-indigo-200	border-color: #c3dafe;	
>   border-indigo-300	border-color: #a3bffa;	
>   border-indigo-400	border-color: #7f9cf5;	
>   border-indigo-500	border-color: #667eea;	
>   border-indigo-600	border-color: #5a67d8;	
>   border-indigo-700	border-color: #4c51bf;	
>   border-indigo-800	border-color: #434190;	
>   border-indigo-900	border-color: #3c366b;	
>   border-purple-100	border-color: #faf5ff;	
>   border-purple-200	border-color: #e9d8fd;	
>   border-purple-300	border-color: #d6bcfa;	
>   border-purple-400	border-color: #b794f4;	
>   border-purple-500	border-color: #9f7aea;	
>   border-purple-600	border-color: #805ad5;	
>   border-purple-700	border-color: #6b46c1;	
>   border-purple-800	border-color: #553c9a;	
>   border-purple-900	border-color: #44337a;	
>   border-pink-100	border-color: #fff5f7;	
>   border-pink-200	border-color: #fed7e2;	
>   border-pink-300	border-color: #fbb6ce;	
>   border-pink-400	border-color: #f687b3;	
>   border-pink-500	border-color: #ed64a6;	
>   border-pink-600	border-color: #d53f8c;	
>   border-pink-700	border-color: #b83280;	
>   border-pink-800	border-color: #97266d;	
>   border-pink-900	border-color: #702459;

## Border Opacity
>   border-opacity-0	--border-opacity: 0;
>   border-opacity-25	--border-opacity: 0.25;
>   border-opacity-50	--border-opacity: 0.5;
>   border-opacity-75	--border-opacity: 0.75;
>   border-opacity-100	--border-opacity: 1;

## Border Style
>   border-solid	border-style: solid;
>   border-dashed	border-style: dashed;
>   border-dotted	border-style: dotted;
>   border-double	border-style: double;
>   border-none	border-style: none;

## Divide Width
>   divide-y-0 > * + *	border-top-width: 0;
>   divide-x-0 > * + *	border-left-width: 0;
>   divide-y-2 > * + *	border-top-width: 2px;
>   divide-x-2 > * + *	border-left-width: 2px;
>   divide-y-4 > * + *	border-top-width: 4px;
>   divide-x-4 > * + *	border-left-width: 4px;
>   divide-y-8 > * + *	border-top-width: 8px;
>   divide-x-8 > * + *	border-left-width: 8px;
>   divide-y > * + *	border-top-width: 1px;
>   divide-x > * + *	border-left-width: 1px;
>   divide-y-reverse > * + *	--divide-y-reverse: 1;
>   divide-x-reverse > * + *	--divide-x-reverse: 1;

## Divide Color
>   divide-transparent > * + *	border-color: transparent;	
>   divide-current > * + *	border-color: currentColor;	
>   divide-black > * + *	border-color: #000;	
>   divide-white > * + *	border-color: #fff;	
>   divide-gray-100 > * + *	border-color: #f7fafc;	
>   divide-gray-200 > * + *	border-color: #edf2f7;	
>   divide-gray-300 > * + *	border-color: #e2e8f0;	
>   divide-gray-400 > * + *	border-color: #cbd5e0;	
>   divide-gray-500 > * + *	border-color: #a0aec0;	
>   divide-gray-600 > * + *	border-color: #718096;	
>   divide-gray-700 > * + *	border-color: #4a5568;	
>   divide-gray-800 > * + *	border-color: #2d3748;	
>   divide-gray-900 > * + *	border-color: #1a202c;	
>   divide-red-100 > * + *	border-color: #fff5f5;	
>   divide-red-200 > * + *	border-color: #fed7d7;	
>   divide-red-300 > * + *	border-color: #feb2b2;	
>   divide-red-400 > * + *	border-color: #fc8181;	
>   divide-red-500 > * + *	border-color: #f56565;	
>   divide-red-600 > * + *	border-color: #e53e3e;	
>   divide-red-700 > * + *	border-color: #c53030;	
>   divide-red-800 > * + *	border-color: #9b2c2c;	
>   divide-red-900 > * + *	border-color: #742a2a;	
>   divide-orange-100 > * + *	border-color: #fffaf0;	
>   divide-orange-200 > * + *	border-color: #feebc8;	
>   divide-orange-300 > * + *	border-color: #fbd38d;	
>   divide-orange-400 > * + *	border-color: #f6ad55;	
>   divide-orange-500 > * + *	border-color: #ed8936;	
>   divide-orange-600 > * + *	border-color: #dd6b20;	
>   divide-orange-700 > * + *	border-color: #c05621;	
>   divide-orange-800 > * + *	border-color: #9c4221;	
>   divide-orange-900 > * + *	border-color: #7b341e;	
>   divide-yellow-100 > * + *	border-color: #fffff0;	
>   divide-yellow-200 > * + *	border-color: #fefcbf;	
>   divide-yellow-300 > * + *	border-color: #faf089;	
>   divide-yellow-400 > * + *	border-color: #f6e05e;	
>   divide-yellow-500 > * + *	border-color: #ecc94b;	
>   divide-yellow-600 > * + *	border-color: #d69e2e;	
>   divide-yellow-700 > * + *	border-color: #b7791f;	
>   divide-yellow-800 > * + *	border-color: #975a16;	
>   divide-yellow-900 > * + *	border-color: #744210;	
>   divide-green-100 > * + *	border-color: #f0fff4;	
>   divide-green-200 > * + *	border-color: #c6f6d5;	
>   divide-green-300 > * + *	border-color: #9ae6b4;	
>   divide-green-400 > * + *	border-color: #68d391;	
>   divide-green-500 > * + *	border-color: #48bb78;	
>   divide-green-600 > * + *	border-color: #38a169;	
>   divide-green-700 > * + *	border-color: #2f855a;	
>   divide-green-800 > * + *	border-color: #276749;	
>   divide-green-900 > * + *	border-color: #22543d;	
>   divide-teal-100 > * + *	border-color: #e6fffa;	
>   divide-teal-200 > * + *	border-color: #b2f5ea;	
>   divide-teal-300 > * + *	border-color: #81e6d9;	
>   divide-teal-400 > * + *	border-color: #4fd1c5;	
>   divide-teal-500 > * + *	border-color: #38b2ac;	
>   divide-teal-600 > * + *	border-color: #319795;	
>   divide-teal-700 > * + *	border-color: #2c7a7b;	
>   divide-teal-800 > * + *	border-color: #285e61;	
>   divide-teal-900 > * + *	border-color: #234e52;	
>   divide-blue-100 > * + *	border-color: #ebf8ff;	
>   divide-blue-200 > * + *	border-color: #bee3f8;	
>   divide-blue-300 > * + *	border-color: #90cdf4;	
>   divide-blue-400 > * + *	border-color: #63b3ed;	
>   divide-blue-500 > * + *	border-color: #4299e1;	
>   divide-blue-600 > * + *	border-color: #3182ce;	
>   divide-blue-700 > * + *	border-color: #2b6cb0;	
>   divide-blue-800 > * + *	border-color: #2c5282;	
>   divide-blue-900 > * + *	border-color: #2a4365;	
>   divide-indigo-100 > * + *	border-color: #ebf4ff;	
>   divide-indigo-200 > * + *	border-color: #c3dafe;	
>   divide-indigo-300 > * + *	border-color: #a3bffa;	
>   divide-indigo-400 > * + *	border-color: #7f9cf5;	
>   divide-indigo-500 > * + *	border-color: #667eea;	
>   divide-indigo-600 > * + *	border-color: #5a67d8;	
>   divide-indigo-700 > * + *	border-color: #4c51bf;	
>   divide-indigo-800 > * + *	border-color: #434190;	
>   divide-indigo-900 > * + *	border-color: #3c366b;	
>   divide-purple-100 > * + *	border-color: #faf5ff;	
>   divide-purple-200 > * + *	border-color: #e9d8fd;	
>   divide-purple-300 > * + *	border-color: #d6bcfa;	
>   divide-purple-400 > * + *	border-color: #b794f4;	
>   divide-purple-500 > * + *	border-color: #9f7aea;	
>   divide-purple-600 > * + *	border-color: #805ad5;	
>   divide-purple-700 > * + *	border-color: #6b46c1;	
>   divide-purple-800 > * + *	border-color: #553c9a;	
>   divide-purple-900 > * + *	border-color: #44337a;	
>   divide-pink-100 > * + *	border-color: #fff5f7;	
>   divide-pink-200 > * + *	border-color: #fed7e2;	
>   divide-pink-300 > * + *	border-color: #fbb6ce;	
>   divide-pink-400 > * + *	border-color: #f687b3;	
>   divide-pink-500 > * + *	border-color: #ed64a6;	
>   divide-pink-600 > * + *	border-color: #d53f8c;	
>   divide-pink-700 > * + *	border-color: #b83280;	
>   divide-pink-800 > * + *	border-color: #97266d;	
>   divide-pink-900 > * + *	border-color: #702459;

## Divide Opacity
>   divide-opacity-0	--divide-opacity: 0;
>   divide-opacity-25	--divide-opacity: 0.25;
>   divide-opacity-50	--divide-opacity: 0.5;
>   divide-opacity-75	--divide-opacity: 0.75;
>   divide-opacity-100	--divide-opacity: 1;

## Divide Style
>   divide-solid > * + *	border-style: solid;
>   divide-dashed > * + *	border-style: dashed;
>   divide-dotted > * + *	border-style: dotted;
>   divide-double > * + *	border-style: double;
>   divide-none > * + *	border-style: none;

# EFFECTS
## Box Shadow
>   shadow-xs	box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.05);
>   shadow-sm	box-shadow: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
>   shadow	box-shadow: 0 1px 3px 0 rgba(0, 0, 0, 0.1), 0 1px 2px 0 rgba(0, 0, 0, 0.06);
>   shadow-md	box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
>   shadow-lg	box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
>   shadow-xl	box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
>   shadow-2xl	box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
>   shadow-inner	box-shadow: inset 0 2px 4px 0 rgba(0, 0, 0, 0.06);
>   shadow-outline	box-shadow: 0 0 0 3px rgba(66, 153, 225, 0.5);
>   shadow-none	box-shadow: none;

## Opacity
>   opacity-0	opacity: 0;
>   opacity-25	opacity: 0.25;
>   opacity-50	opacity: 0.5;
>   opacity-75	opacity: 0.75;
>   opacity-100	opacity: 1; 

# FLEXBOX
## Flex Direction
>   flex-row	flex-direction: row;
>   flex-row-reverse	flex-direction: row-reverse;
>   flex-col	flex-direction: column;
>   flex-col-reverse	flex-direction: column-reverse;

## Flex Wrap
>   flex-wrap	flex-wrap: wrap;
>   flex-wrap-reverse	flex-wrap: wrap-reverse;
>   flex-no-wrap	flex-wrap: nowrap;

## Flex
>   flex-1	flex: 1 1 0%;
>   flex-auto	flex: 1 1 auto;
>   flex-initial	flex: 0 1 auto;
>   flex-none	flex: none;

## Flex Grow
>   flex-grow-0	flex-grow: 0;
>   flex-grow	flex-grow: 1;

## Flex Shrink
>   flex-shrink-0	flex-shrink: 0;
>   flex-shrink	flex-shrink: 1;

## Order
>   order-1	order: 1;
>   order-2	order: 2;
>   order-3	order: 3;
>   order-4	order: 4;
>   order-5	order: 5;
>   order-6	order: 6;
>   order-7	order: 7;
>   order-8	order: 8;
>   order-9	order: 9;
>   order-10	order: 10;
>   order-11	order: 11;
>   order-12	order: 12;
>   order-first	order: -9999;
>   order-last	order: 9999;
>   order-none	

# GRID
## Grid Template Columns
>   grid-cols-1	grid-template-columns: repeat(1, minmax(0, 1fr));
>   grid-cols-2	grid-template-columns: repeat(2, minmax(0, 1fr));
>   grid-cols-3	grid-template-columns: repeat(3, minmax(0, 1fr));
>   grid-cols-4	grid-template-columns: repeat(4, minmax(0, 1fr));
>   grid-cols-5	grid-template-columns: repeat(5, minmax(0, 1fr));
>   grid-cols-6	grid-template-columns: repeat(6, minmax(0, 1fr));
>   grid-cols-7	grid-template-columns: repeat(7, minmax(0, 1fr));
>   grid-cols-8	grid-template-columns: repeat(8, minmax(0, 1fr));
>   grid-cols-9	grid-template-columns: repeat(9, minmax(0, 1fr));
>   grid-cols-10	grid-template-columns: repeat(10, minmax(0, 1fr));
>   grid-cols-11	grid-template-columns: repeat(11, minmax(0, 1fr));
>   grid-cols-12	grid-template-columns: repeat(12, minmax(0, 1fr));
>   grid-cols-none	grid-template-columns: none;

## Grid Column Start / End
>   col-auto	grid-column: auto;
>   col-span-1	grid-column: span 1 / span 1;
>   col-span-2	grid-column: span 2 / span 2;
>   col-span-3	grid-column: span 3 / span 3;
>   col-span-4	grid-column: span 4 / span 4;
>   col-span-5	grid-column: span 5 / span 5;
>   col-span-6	grid-column: span 6 / span 6;
>   col-span-7	grid-column: span 7 / span 7;
>   col-span-8	grid-column: span 8 / span 8;
>   col-span-9	grid-column: span 9 / span 9;
>   col-span-10	grid-column: span 10 / span 10;
>   col-span-11	grid-column: span 11 / span 11;
>   col-span-12	grid-column: span 12 / span 12;
>   col-start-1	grid-column-start: 1;
>   col-start-2	grid-column-start: 2;
>   col-start-3	grid-column-start: 3;
>   col-start-4	grid-column-start: 4;
>   col-start-5	grid-column-start: 5;
>   col-start-6	grid-column-start: 6;
>   col-start-7	grid-column-start: 7;
>   col-start-8	grid-column-start: 8;
>   col-start-9	grid-column-start: 9;
>   col-start-10	grid-column-start: 10;
>   col-start-11	grid-column-start: 11;
>   col-start-12	grid-column-start: 12;
>   col-start-13	grid-column-start: 13;
>   col-start-auto	grid-column-start: auto;
>   col-end-1	grid-column-end: 1;
>   col-end-2	grid-column-end: 2;
>   col-end-3	grid-column-end: 3;
>   col-end-4	grid-column-end: 4;
>   col-end-5	grid-column-end: 5;
>   col-end-6	grid-column-end: 6;
>   col-end-7	grid-column-end: 7;
>   col-end-8	grid-column-end: 8;
>   col-end-9	grid-column-end: 9;
>   col-end-10	grid-column-end: 10;
>   col-end-11	grid-column-end: 11;
>   col-end-12	grid-column-end: 12;
>   col-end-13	grid-column-end: 13;
>   col-end-auto	grid-column-end: auto;

## Grid Template Rows
>   grid-rows-1	grid-template-rows: repeat(1, minmax(0, 1fr));
>   grid-rows-2	grid-template-rows: repeat(2, minmax(0, 1fr));
>   grid-rows-3	grid-template-rows: repeat(3, minmax(0, 1fr));
>   grid-rows-4	grid-template-rows: repeat(4, minmax(0, 1fr));
>   grid-rows-5	grid-template-rows: repeat(5, minmax(0, 1fr));
>   grid-rows-6	grid-template-rows: repeat(6, minmax(0, 1fr));
>   grid-rows-none	grid-template-rows: none;

## Grid Row Start / End
>   row-auto	grid-row: auto;
>   row-span-1	grid-row: span 1 / span 1;
>   row-span-2	grid-row: span 2 / span 2;
>   row-span-3	grid-row: span 3 / span 3;
>   row-span-4	grid-row: span 4 / span 4;
>   row-span-5	grid-row: span 5 / span 5;
>   row-span-6	grid-row: span 6 / span 6;
>   row-start-1	grid-row-start: 1;
>   row-start-2	grid-row-start: 2;
>   row-start-3	grid-row-start: 3;
>   row-start-4	grid-row-start: 4;
>   row-start-5	grid-row-start: 5;
>   row-start-6	grid-row-start: 6;
>   row-start-7	grid-row-start: 7;
>   row-start-auto	grid-row-start: auto;
>   row-end-1	grid-row-end: 1;
>   row-end-2	grid-row-end: 2;
>   row-end-3	grid-row-end: 3;
>   row-end-4	grid-row-end: 4;
>   row-end-5	grid-row-end: 5;
>   row-end-6	grid-row-end: 6;
>   row-end-7	grid-row-end: 7;
>   row-end-auto	grid-row-end: auto;

## Grid Auto Flow
>   grid-flow-row	grid-auto-flow: row;
>   grid-flow-col	grid-auto-flow: column;
>   grid-flow-row-dense	grid-auto-flow: row dense;
>   grid-flow-col-dense	grid-auto-flow: column dense;

## Gap
>   gap-0	gap: 0;
>   gap-1	gap: 0.25rem;
>   gap-2	gap: 0.5rem;
>   gap-3	gap: 0.75rem;
>   gap-4	gap: 1rem;
>   gap-5	gap: 1.25rem;
>   gap-6	gap: 1.5rem;
>   gap-8	gap: 2rem;
>   gap-10	gap: 2.5rem;
>   gap-12	gap: 3rem;
>   gap-16	gap: 4rem;
>   gap-20	gap: 5rem;
>   gap-24	gap: 6rem;
>   gap-32	gap: 8rem;
>   gap-40	gap: 10rem;
>   gap-48	gap: 12rem;
>   gap-56	gap: 14rem;
>   gap-64	gap: 16rem;
>   gap-px	gap: 1px;
>   gap-x-0	column-gap: 0;
>   gap-x-1	column-gap: 0.25rem;
>   gap-x-2	column-gap: 0.5rem;
>   gap-x-3	column-gap: 0.75rem;
>   gap-x-4	column-gap: 1rem;
>   gap-x-5	column-gap: 1.25rem;
>   gap-x-6	column-gap: 1.5rem;
>   gap-x-8	column-gap: 2rem;
>   gap-x-10	column-gap: 2.5rem;
>   gap-x-12	column-gap: 3rem;
>   gap-x-16	column-gap: 4rem;
>   gap-x-20	column-gap: 5rem;
>   gap-x-24	column-gap: 6rem;
>   gap-x-32	column-gap: 8rem;
>   gap-x-40	column-gap: 10rem;
>   gap-x-48	column-gap: 12rem;
>   gap-x-56	column-gap: 14rem;
>   gap-x-64	column-gap: 16rem;
>   gap-x-px	column-gap: 1px;
>   gap-y-0	row-gap: 0;
>   gap-y-1	row-gap: 0.25rem;
>   gap-y-2	row-gap: 0.5rem;
>   gap-y-3	row-gap: 0.75rem;
>   gap-y-4	row-gap: 1rem;
>   gap-y-5	row-gap: 1.25rem;
>   gap-y-6	row-gap: 1.5rem;
>   gap-y-8	row-gap: 2rem;
>   gap-y-10	row-gap: 2.5rem;
>   gap-y-12	row-gap: 3rem;
>   gap-y-16	row-gap: 4rem;
>   gap-y-20	row-gap: 5rem;
>   gap-y-24	row-gap: 6rem;
>   gap-y-32	row-gap: 8rem;
>   gap-y-40	row-gap: 10rem;
>   gap-y-48	row-gap: 12rem;
>   gap-y-56	row-gap: 14rem;
>   gap-y-64	row-gap: 16rem;
>   gap-y-px	row-gap: 1px;

# BOX ALIGNMENT
## Justify Content
>   justify-start	justify-content: flex-start;
>   justify-end	justify-content: flex-end;
>   justify-center	justify-content: center;
>   justify-between	justify-content: space-between;
>   justify-around	justify-content: space-around;
>   justify-evenly	justify-content: space-evenly;

## Justify Items
>   justify-items-auto	justify-items: auto;
>   justify-items-start	justify-items: start;
>   justify-items-end	justify-items: end;
>   justify-items-center	justify-items: center;
>   justify-items-stretch	justify-items: stretch;

## Justify Self
>   justify-self-auto	justify-self: auto;
>   justify-self-start	justify-self: start;
>   justify-self-end	justify-self: end;
>   justify-self-center	justify-self: center;
>   justify-self-stretch	justify-self: stretch;

## Align Content
>   content-center	align-content: center;
>   content-start	align-content: flex-start;
>   content-end	align-content: flex-end;
>   content-between	align-content: space-between;
>   content-around	align-content: space-around;
>   content-evenly	align-content: space-evenly;

## Align Items
>   items-start	align-items: flex-start;
>   items-end	align-items: flex-end;
>   items-center	align-items: center;
>   items-baseline	align-items: baseline;
>   items-stretch	align-items: stretch;

## Align Self
>   self-auto	align-self: auto;
>   self-start	align-self: flex-start;
>   self-end	align-self: flex-end;
>   self-center	align-self: center;
>   self-stretch	align-self: stretch;

## Place Content
>   place-content-center	place-content: center;
>   place-content-start	place-content: start;
>   place-content-end	place-content: end;
>   place-content-between	place-content: space-between;
>   place-content-around	place-content: space-around;
>   place-content-evenly	place-content: space-evenly;
>   place-content-stretch	place-content: stretch;

## Place Items
>   place-items-auto	place-items: auto;
>   place-items-start	place-items: start;
>   place-items-end	place-items: end;
>   place-items-center	place-items: center;
>   place-items-stretch	place-items: stretch;

## Place Self
>   place-self-auto	place-self: auto;
>   place-self-start	place-self: start;
>   place-self-end	place-self: end;
>   place-self-center	place-self: center;
>   place-self-stretch	place-self: stretch;

# SPACING
## Padding
>   p-0	padding: 0;
>   p-1	padding: 0.25rem;
>   p-2	padding: 0.5rem;
>   p-3	padding: 0.75rem;
>   p-4	padding: 1rem;
>   p-5	padding: 1.25rem;
>   p-6	padding: 1.5rem;
>   p-8	padding: 2rem;
>   p-10	padding: 2.5rem;
>   p-12	padding: 3rem;
>   p-16	padding: 4rem;
>   p-20	padding: 5rem;
>   p-24	padding: 6rem;
>   p-32	padding: 8rem;
>   p-40	padding: 10rem;
>   p-48	padding: 12rem;
>   p-56	padding: 14rem;
>   p-64	padding: 16rem;
>   p-px	padding: 1px;
>   py-0	padding-top: 0;
>           padding-bottom: 0;
>   px-0	padding-left: 0;
>           padding-right: 0;
>   py-1	padding-top: 0.25rem;
>           padding-bottom: 0.25rem;
>   px-1	padding-left: 0.25rem;
>           padding-right: 0.25rem;
>   py-2	padding-top: 0.5rem;
>           padding-bottom: 0.5rem;
>   px-2	padding-left: 0.5rem;
>           padding-right: 0.5rem;
>   py-3	padding-top: 0.75rem;
>           padding-bottom: 0.75rem;
>   px-3	padding-left: 0.75rem;
>           padding-right: 0.75rem;
>   py-4	padding-top: 1rem;
>           padding-bottom: 1rem;
>   px-4	padding-left: 1rem;
>           padding-right: 1rem;
>   py-5	padding-top: 1.25rem;
>           padding-bottom: 1.25rem;
>   px-5	padding-left: 1.25rem;
>           padding-right: 1.25rem;
>   py-6	padding-top: 1.5rem;
>           padding-bottom: 1.5rem;
>   px-6	padding-left: 1.5rem;
>           padding-right: 1.5rem;
>   py-8	padding-top: 2rem;
>           padding-bottom: 2rem;
>   px-8	padding-left: 2rem;
>           padding-right: 2rem;
>   py-10	padding-top: 2.5rem;
>           padding-bottom: 2.5rem;
>   px-10	padding-left: 2.5rem;
>           padding-right: 2.5rem;
>   py-12	padding-top: 3rem;
>           padding-bottom: 3rem;
>   px-12	padding-left: 3rem;
>           padding-right: 3rem;
>   py-16	padding-top: 4rem;
>           padding-bottom: 4rem;
>   px-16	padding-left: 4rem;
>           padding-right: 4rem;
>   py-20	padding-top: 5rem;
>           padding-bottom: 5rem;
>   px-20	padding-left: 5rem;
>           padding-right: 5rem;
>   py-24	padding-top: 6rem;
>           padding-bottom: 6rem;
>   px-24	padding-left: 6rem;
>           padding-right: 6rem;
>   py-32	padding-top: 8rem;
>           padding-bottom: 8rem;
>   px-32	padding-left: 8rem;
>           padding-right: 8rem;
>   py-40	padding-top: 10rem;
>           padding-bottom: 10rem;
>   px-40	padding-left: 10rem;
>           padding-right: 10rem;
>   py-48	padding-top: 12rem;
>           padding-bottom: 12rem;
>   px-48	padding-left: 12rem;
>           padding-right: 12rem;
>   py-56	padding-top: 14rem;
>           padding-bottom: 14rem;
>   px-56	padding-left: 14rem;
>           padding-right: 14rem;
>   py-64	padding-top: 16rem;
>           padding-bottom: 16rem;
>   px-64	padding-left: 16rem;
>           padding-right: 16rem;
>   py-px	padding-top: 1px;
>           padding-bottom: 1px;
>   px-px	padding-left: 1px;
>           padding-right: 1px;
>   pt-0	padding-top: 0;
>   pr-0	padding-right: 0;
>   pb-0	padding-bottom: 0;
>   pl-0	padding-left: 0;
>   pt-1	padding-top: 0.25rem;
>   pr-1	padding-right: 0.25rem;
>   pb-1	padding-bottom: 0.25rem;
>   pl-1	padding-left: 0.25rem;
>   pt-2	padding-top: 0.5rem;
>   pr-2	padding-right: 0.5rem;
>   pb-2	padding-bottom: 0.5rem;
>   pl-2	padding-left: 0.5rem;
>   pt-3	padding-top: 0.75rem;
>   pr-3	padding-right: 0.75rem;
>   pb-3	padding-bottom: 0.75rem;
>   pl-3	padding-left: 0.75rem;
>   pt-4	padding-top: 1rem;
>   pr-4	padding-right: 1rem;
>   pb-4	padding-bottom: 1rem;
>   pl-4	padding-left: 1rem;
>   pt-5	padding-top: 1.25rem;
>   pr-5	padding-right: 1.25rem;
>   pb-5	padding-bottom: 1.25rem;
>   pl-5	padding-left: 1.25rem;
>   pt-6	padding-top: 1.5rem;
>   pr-6	padding-right: 1.5rem;
>   pb-6	padding-bottom: 1.5rem;
>   pl-6	padding-left: 1.5rem;
>   pt-8	padding-top: 2rem;
>   pr-8	padding-right: 2rem;
>   pb-8	padding-bottom: 2rem;
>   pl-8	padding-left: 2rem;
>   pt-10	padding-top: 2.5rem;
>   pr-10	padding-right: 2.5rem;
>   pb-10	padding-bottom: 2.5rem;
>   pl-10	padding-left: 2.5rem;
>   pt-12	padding-top: 3rem;
>   pr-12	padding-right: 3rem;
>   pb-12	padding-bottom: 3rem;
>   pl-12	padding-left: 3rem;
>   pt-16	padding-top: 4rem;
>   pr-16	padding-right: 4rem;
>   pb-16	padding-bottom: 4rem;
>   pl-16	padding-left: 4rem;
>   pt-20	padding-top: 5rem;
>   pr-20	padding-right: 5rem;
>   pb-20	padding-bottom: 5rem;
>   pl-20	padding-left: 5rem;
>   pt-24	padding-top: 6rem;
>   pr-24	padding-right: 6rem;
>   pb-24	padding-bottom: 6rem;
>   pl-24	padding-left: 6rem;
>   pt-32	padding-top: 8rem;
>   pr-32	padding-right: 8rem;
>   pb-32	padding-bottom: 8rem;
>   pl-32	padding-left: 8rem;
>   pt-40	padding-top: 10rem;
>   pr-40	padding-right: 10rem;
>   pb-40	padding-bottom: 10rem;
>   pl-40	padding-left: 10rem;
>   pt-48	padding-top: 12rem;
>   pr-48	padding-right: 12rem;
>   pb-48	padding-bottom: 12rem;
>   pl-48	padding-left: 12rem;
>   pt-56	padding-top: 14rem;
>   pr-56	padding-right: 14rem;
>   pb-56	padding-bottom: 14rem;
>   pl-56	padding-left: 14rem;
>   pt-64	padding-top: 16rem;
>   pr-64	padding-right: 16rem;
>   pb-64	padding-bottom: 16rem;
>   pl-64	padding-left: 16rem;
>   pt-px	padding-top: 1px;
>   pr-px	padding-right: 1px;
>   pb-px	padding-bottom: 1px;
>   pl-px	padding-left: 1px;

## Margin
>   m-0	margin: 0;
>   m-1	margin: 0.25rem;
>   m-2	margin: 0.5rem;
>   m-3	margin: 0.75rem;
>   m-4	margin: 1rem;
>   m-5	margin: 1.25rem;
>   m-6	margin: 1.5rem;
>   m-8	margin: 2rem;
>   m-10	margin: 2.5rem;
>   m-12	margin: 3rem;
>   m-16	margin: 4rem;
>   m-20	margin: 5rem;
>   m-24	margin: 6rem;
>   m-32	margin: 8rem;
>   m-40	margin: 10rem;
>   m-48	margin: 12rem;
>   m-56	margin: 14rem;
>   m-64	margin: 16rem;
>   m-auto	margin: auto;
>   m-px	margin: 1px;
>   -m-1	margin: -0.25rem;
>   -m-2	margin: -0.5rem;
>   -m-3	margin: -0.75rem;
>   -m-4	margin: -1rem;
>   -m-5	margin: -1.25rem;
>   -m-6	margin: -1.5rem;
>   -m-8	margin: -2rem;
>   -m-10	margin: -2.5rem;
>   -m-12	margin: -3rem;
>   -m-16	margin: -4rem;
>   -m-20	margin: -5rem;
>   -m-24	margin: -6rem;
>   -m-32	margin: -8rem;
>   -m-40	margin: -10rem;
>   -m-48	margin: -12rem;
>   -m-56	margin: -14rem;
>   -m-64	margin: -16rem;
>   -m-px	margin: -1px;
>   my-0	margin-top: 0;
>           margin-bottom: 0;
>   mx-0	margin-left: 0;
>           margin-right: 0;
>   my-1	margin-top: 0.25rem;
>           margin-bottom: 0.25rem;
>   mx-1	margin-left: 0.25rem;
>           margin-right: 0.25rem;
>   my-2	margin-top: 0.5rem;
>           margin-bottom: 0.5rem;
>   mx-2	margin-left: 0.5rem;
>           margin-right: 0.5rem;
>   my-3	margin-top: 0.75rem;
>           margin-bottom: 0.75rem;
>   mx-3	margin-left: 0.75rem;
>           margin-right: 0.75rem;
>   my-4	margin-top: 1rem;
>           margin-bottom: 1rem;
>   mx-4	margin-left: 1rem;
>           margin-right: 1rem;
>   my-5	margin-top: 1.25rem;
>           margin-bottom: 1.25rem;
>   mx-5	margin-left: 1.25rem;
>           margin-right: 1.25rem;
>   my-6	margin-top: 1.5rem;
>           margin-bottom: 1.5rem;
>   mx-6	margin-left: 1.5rem;
>           margin-right: 1.5rem;
>   my-8	margin-top: 2rem;
>           margin-bottom: 2rem;
>   mx-8	margin-left: 2rem;
>           margin-right: 2rem;
>   my-10	margin-top: 2.5rem;
>           margin-bottom: 2.5rem;
>   mx-10	margin-left: 2.5rem;
>           margin-right: 2.5rem;
>   my-12	margin-top: 3rem;
>           margin-bottom: 3rem;
>   mx-12	margin-left: 3rem;
>           margin-right: 3rem;
>   my-16	margin-top: 4rem;
>           margin-bottom: 4rem;
>   mx-16	margin-left: 4rem;
>           margin-right: 4rem;
>   my-20	margin-top: 5rem;
>           margin-bottom: 5rem;
>   mx-20	margin-left: 5rem;
>           margin-right: 5rem;
>   my-24	margin-top: 6rem;
>           margin-bottom: 6rem;
>   mx-24	margin-left: 6rem;
>           margin-right: 6rem;
>   my-32	margin-top: 8rem;
>           margin-bottom: 8rem;
>   mx-32	margin-left: 8rem;
>           margin-right: 8rem;
>   my-40	margin-top: 10rem;
>           margin-bottom: 10rem;
>   mx-40	margin-left: 10rem;
>           margin-right: 10rem;
>   my-48	margin-top: 12rem;
>           margin-bottom: 12rem;
>   mx-48	margin-left: 12rem;
>           margin-right: 12rem;
>   my-56	margin-top: 14rem;
>           margin-bottom: 14rem;
>   mx-56	margin-left: 14rem;
>           margin-right: 14rem;
>   my-64	margin-top: 16rem;
>           margin-bottom: 16rem;
>   mx-64	margin-left: 16rem;
>           margin-right: 16rem;
>   my-auto	margin-top: auto;
>           margin-bottom: auto;
>   mx-auto	margin-left: auto;
>           margin-right: auto;
>   my-px	margin-top: 1px;
>           margin-bottom: 1px;
>   mx-px	margin-left: 1px;
>           margin-right: 1px;
>   -my-1	margin-top: -0.25rem;
>           margin-bottom: -0.25rem;
>   -mx-1	margin-left: -0.25rem;
>           margin-right: -0.25rem;
>   -my-2	margin-top: -0.5rem;
>           margin-bottom: -0.5rem;
>   -mx-2	margin-left: -0.5rem;
>           margin-right: -0.5rem;
>   -my-3	margin-top: -0.75rem;
>           margin-bottom: -0.75rem;
>   -mx-3	margin-left: -0.75rem;
>           margin-right: -0.75rem;
>   -my-4	margin-top: -1rem;
>           margin-bottom: -1rem;
>   -mx-4	margin-left: -1rem;
>           margin-right: -1rem;
>   -my-5	margin-top: -1.25rem;
>           margin-bottom: -1.25rem;
>   -mx-5	margin-left: -1.25rem;
>           margin-right: -1.25rem;
>   -my-6	margin-top: -1.5rem;
>           margin-bottom: -1.5rem;
>   -mx-6	margin-left: -1.5rem;
>           margin-right: -1.5rem;
>   -my-8	margin-top: -2rem;
>           margin-bottom: -2rem;
>   -mx-8	margin-left: -2rem;
>           margin-right: -2rem;
>   -my-10	margin-top: -2.5rem;
>           margin-bottom: -2.5rem;
>   -mx-10	margin-left: -2.5rem;
>           margin-right: -2.5rem;
>   -my-12	margin-top: -3rem;
>           margin-bottom: -3rem;
>   -mx-12	margin-left: -3rem;
>           margin-right: -3rem;
>   -my-16	margin-top: -4rem;
>           margin-bottom: -4rem;
>   -mx-16	margin-left: -4rem;
>           margin-right: -4rem;
>   -my-20	margin-top: -5rem;
>           margin-bottom: -5rem;
>   -mx-20	margin-left: -5rem;
>           margin-right: -5rem;
>   -my-24	margin-top: -6rem;
>           margin-bottom: -6rem;
>   -mx-24	margin-left: -6rem;
>           margin-right: -6rem;
>   -my-32	margin-top: -8rem;
>           margin-bottom: -8rem;
>   -mx-32	margin-left: -8rem;
>           margin-right: -8rem;
>   -my-40	margin-top: -10rem;
>           margin-bottom: -10rem;
>   -mx-40	margin-left: -10rem;
>           margin-right: -10rem;
>   -my-48	margin-top: -12rem;
>           margin-bottom: -12rem;
>   -mx-48	margin-left: -12rem;
>           margin-right: -12rem;
>   -my-56	margin-top: -14rem;
>           margin-bottom: -14rem;
>   -mx-56	margin-left: -14rem;
>           margin-right: -14rem;
>   -my-64	margin-top: -16rem;
>           margin-bottom: -16rem;
>   -mx-64	margin-left: -16rem;
>           margin-right: -16rem;
>   -my-px	margin-top: -1px;
>           margin-bottom: -1px;
>   -mx-px	margin-left: -1px;
>           margin-right: -1px;
>   mt-0	margin-top: 0;
>   mr-0	margin-right: 0;
>   mb-0	margin-bottom: 0;
>   ml-0	margin-left: 0;
>   mt-1	margin-top: 0.25rem;
>   mr-1	margin-right: 0.25rem;
>   mb-1	margin-bottom: 0.25rem;
>   ml-1	margin-left: 0.25rem;
>   mt-2	margin-top: 0.5rem;
>   mr-2	margin-right: 0.5rem;
>   mb-2	margin-bottom: 0.5rem;
>   ml-2	margin-left: 0.5rem;
>   mt-3	margin-top: 0.75rem;
>   mr-3	margin-right: 0.75rem;
>   mb-3	margin-bottom: 0.75rem;
>   ml-3	margin-left: 0.75rem;
>   mt-4	margin-top: 1rem;
>   mr-4	margin-right: 1rem;
>   mb-4	margin-bottom: 1rem;
>   ml-4	margin-left: 1rem;
>   mt-5	margin-top: 1.25rem;
>   mr-5	margin-right: 1.25rem;
>   mb-5	margin-bottom: 1.25rem;
>   ml-5	margin-left: 1.25rem;
>   mt-6	margin-top: 1.5rem;
>   mr-6	margin-right: 1.5rem;
>   mb-6	margin-bottom: 1.5rem;
>   ml-6	margin-left: 1.5rem;
>   mt-8	margin-top: 2rem;
>   mr-8	margin-right: 2rem;
>   mb-8	margin-bottom: 2rem;
>   ml-8	margin-left: 2rem;
>   mt-10	margin-top: 2.5rem;
>   mr-10	margin-right: 2.5rem;
>   mb-10	margin-bottom: 2.5rem;
>   ml-10	margin-left: 2.5rem;
>   mt-12	margin-top: 3rem;
>   mr-12	margin-right: 3rem;
>   mb-12	margin-bottom: 3rem;
>   ml-12	margin-left: 3rem;
>   mt-16	margin-top: 4rem;
>   mr-16	margin-right: 4rem;
>   mb-16	margin-bottom: 4rem;
>   ml-16	margin-left: 4rem;
>   mt-20	margin-top: 5rem;
>   mr-20	margin-right: 5rem;
>   mb-20	margin-bottom: 5rem;
>   ml-20	margin-left: 5rem;
>   mt-24	margin-top: 6rem;
>   mr-24	margin-right: 6rem;
>   mb-24	margin-bottom: 6rem;
>   ml-24	margin-left: 6rem;
>   mt-32	margin-top: 8rem;
>   mr-32	margin-right: 8rem;
>   mb-32	margin-bottom: 8rem;
>   ml-32	margin-left: 8rem;
>   mt-40	margin-top: 10rem;
>   mr-40	margin-right: 10rem;
>   mb-40	margin-bottom: 10rem;
>   ml-40	margin-left: 10rem;
>   mt-48	margin-top: 12rem;
>   mr-48	margin-right: 12rem;
>   mb-48	margin-bottom: 12rem;
>   ml-48	margin-left: 12rem;
>   mt-56	margin-top: 14rem;
>   mr-56	margin-right: 14rem;
>   mb-56	margin-bottom: 14rem;
>   ml-56	margin-left: 14rem;
>   mt-64	margin-top: 16rem;
>   mr-64	margin-right: 16rem;
>   mb-64	margin-bottom: 16rem;
>   ml-64	margin-left: 16rem;
>   mt-auto	margin-top: auto;
>   mr-auto	margin-right: auto;
>   mb-auto	margin-bottom: auto;
>   ml-auto	margin-left: auto;
>   mt-px	margin-top: 1px;
>   mr-px	margin-right: 1px;
>   mb-px	margin-bottom: 1px;
>   ml-px	margin-left: 1px;
>   -mt-1	margin-top: -0.25rem;
>   -mr-1	margin-right: -0.25rem;
>   -mb-1	margin-bottom: -0.25rem;
>   -ml-1	margin-left: -0.25rem;
>   -mt-2	margin-top: -0.5rem;
>   -mr-2	margin-right: -0.5rem;
>   -mb-2	margin-bottom: -0.5rem;
>   -ml-2	margin-left: -0.5rem;
>   -mt-3	margin-top: -0.75rem;
>   -mr-3	margin-right: -0.75rem;
>   -mb-3	margin-bottom: -0.75rem;
>   -ml-3	margin-left: -0.75rem;
>   -mt-4	margin-top: -1rem;
>   -mr-4	margin-right: -1rem;
>   -mb-4	margin-bottom: -1rem;
>   -ml-4	margin-left: -1rem;
>   -mt-5	margin-top: -1.25rem;
>   -mr-5	margin-right: -1.25rem;
>   -mb-5	margin-bottom: -1.25rem;
>   -ml-5	margin-left: -1.25rem;
>   -mt-6	margin-top: -1.5rem;
>   -mr-6	margin-right: -1.5rem;
>   -mb-6	margin-bottom: -1.5rem;
>   -ml-6	margin-left: -1.5rem;
>   -mt-8	margin-top: -2rem;
>   -mr-8	margin-right: -2rem;
>   -mb-8	margin-bottom: -2rem;
>   -ml-8	margin-left: -2rem;
>   -mt-10	margin-top: -2.5rem;
>   -mr-10	margin-right: -2.5rem;
>   -mb-10	margin-bottom: -2.5rem;
>   -ml-10	margin-left: -2.5rem;
>   -mt-12	margin-top: -3rem;
>   -mr-12	margin-right: -3rem;
>   -mb-12	margin-bottom: -3rem;
>   -ml-12	margin-left: -3rem;
>   -mt-16	margin-top: -4rem;
>   -mr-16	margin-right: -4rem;
>   -mb-16	margin-bottom: -4rem;
>   -ml-16	margin-left: -4rem;
>   -mt-20	margin-top: -5rem;
>   -mr-20	margin-right: -5rem;
>   -mb-20	margin-bottom: -5rem;
>   -ml-20	margin-left: -5rem;
>   -mt-24	margin-top: -6rem;
>   -mr-24	margin-right: -6rem;
>   -mb-24	margin-bottom: -6rem;
>   -ml-24	margin-left: -6rem;
>   -mt-32	margin-top: -8rem;
>   -mr-32	margin-right: -8rem;
>   -mb-32	margin-bottom: -8rem;
>   -ml-32	margin-left: -8rem;
>   -mt-40	margin-top: -10rem;
>   -mr-40	margin-right: -10rem;
>   -mb-40	margin-bottom: -10rem;
>   -ml-40	margin-left: -10rem;
>   -mt-48	margin-top: -12rem;
>   -mr-48	margin-right: -12rem;
>   -mb-48	margin-bottom: -12rem;
>   -ml-48	margin-left: -12rem;
>   -mt-56	margin-top: -14rem;
>   -mr-56	margin-right: -14rem;
>   -mb-56	margin-bottom: -14rem;
>   -ml-56	margin-left: -14rem;
>   -mt-64	margin-top: -16rem;
>   -mr-64	margin-right: -16rem;
>   -mb-64	margin-bottom: -16rem;
>   -ml-64	margin-left: -16rem;
>   -mt-px	margin-top: -1px;
>   -mr-px	margin-right: -1px;
>   -mb-px	margin-bottom: -1px;
>   -ml-px	margin-left: -1px;

## Space Between
>   space-y-0 > * + *	margin-top: 0;
>   space-x-0 > * + *	margin-left: 0;
>   space-y-1 > * + *	margin-top: 0.25rem;
>   space-x-1 > * + *	margin-left: 0.25rem;
>   space-y-2 > * + *	margin-top: 0.5rem;
>   space-x-2 > * + *	margin-left: 0.5rem;
>   space-y-3 > * + *	margin-top: 0.75rem;
>   space-x-3 > * + *	margin-left: 0.75rem;
>   space-y-4 > * + *	margin-top: 1rem;
>   space-x-4 > * + *	margin-left: 1rem;
>   space-y-5 > * + *	margin-top: 1.25rem;
>   space-x-5 > * + *	margin-left: 1.25rem;
>   space-y-6 > * + *	margin-top: 1.5rem;
>   space-x-6 > * + *	margin-left: 1.5rem;
>   space-y-8 > * + *	margin-top: 2rem;
>   space-x-8 > * + *	margin-left: 2rem;
>   space-y-10 > * + *	margin-top: 2.5rem;
>   space-x-10 > * + *	margin-left: 2.5rem;
>   space-y-12 > * + *	margin-top: 3rem;
>   space-x-12 > * + *	margin-left: 3rem;
>   space-y-16 > * + *	margin-top: 4rem;
>   space-x-16 > * + *	margin-left: 4rem;
>   space-y-20 > * + *	margin-top: 5rem;
>   space-x-20 > * + *	margin-left: 5rem;
>   space-y-24 > * + *	margin-top: 6rem;
>   space-x-24 > * + *	margin-left: 6rem;
>   space-y-32 > * + *	margin-top: 8rem;
>   space-x-32 > * + *	margin-left: 8rem;
>   space-y-40 > * + *	margin-top: 10rem;
>   space-x-40 > * + *	margin-left: 10rem;
>   space-y-48 > * + *	margin-top: 12rem;
>   space-x-48 > * + *	margin-left: 12rem;
>   space-y-56 > * + *	margin-top: 14rem;
>   space-x-56 > * + *	margin-left: 14rem;
>   space-y-64 > * + *	margin-top: 16rem;
>   space-x-64 > * + *	margin-left: 16rem;
>   space-y-px > * + *	margin-top: 1px;
>   space-x-px > * + *	margin-left: 1px;
>   -space-y-1 > * + *	margin-top: -0.25rem;
>   -space-x-1 > * + *	margin-left: -0.25rem;
>   -space-y-2 > * + *	margin-top: -0.5rem;
>   -space-x-2 > * + *	margin-left: -0.5rem;
>   -space-y-3 > * + *	margin-top: -0.75rem;
>   -space-x-3 > * + *	margin-left: -0.75rem;
>   -space-y-4 > * + *	margin-top: -1rem;
>   -space-x-4 > * + *	margin-left: -1rem;
>   -space-y-5 > * + *	margin-top: -1.25rem;
>   -space-x-5 > * + *	margin-left: -1.25rem;
>   -space-y-6 > * + *	margin-top: -1.5rem;
>   -space-x-6 > * + *	margin-left: -1.5rem;
>   -space-y-8 > * + *	margin-top: -2rem;
>   -space-x-8 > * + *	margin-left: -2rem;
>   -space-y-10 > * + *	margin-top: -2.5rem;
>   -space-x-10 > * + *	margin-left: -2.5rem;
>   -space-y-12 > * + *	margin-top: -3rem;
>   -space-x-12 > * + *	margin-left: -3rem;
>   -space-y-16 > * + *	margin-top: -4rem;
>   -space-x-16 > * + *	margin-left: -4rem;
>   -space-y-20 > * + *	margin-top: -5rem;
>   -space-x-20 > * + *	margin-left: -5rem;
>   -space-y-24 > * + *	margin-top: -6rem;
>   -space-x-24 > * + *	margin-left: -6rem;
>   -space-y-32 > * + *	margin-top: -8rem;
>   -space-x-32 > * + *	margin-left: -8rem;
>   -space-y-40 > * + *	margin-top: -10rem;
>   -space-x-40 > * + *	margin-left: -10rem;
>   -space-y-48 > * + *	margin-top: -12rem;
>   -space-x-48 > * + *	margin-left: -12rem;
>   -space-y-56 > * + *	margin-top: -14rem;
>   -space-x-56 > * + *	margin-left: -14rem;
>   -space-y-64 > * + *	margin-top: -16rem;
>   -space-x-64 > * + *	margin-left: -16rem;
>   -space-y-px > * + *	margin-top: -1px;
>   -space-x-px > * + *	margin-left: -1px;
>   space-y-reverse > * + *	--space-y-reverse: 1;
>   space-x-reverse > * + *	--space-x-reverse: 1;

# SIZING
## Width
>   w-0	    width: 0;
>   w-1	    width: 0.25rem;
>   w-2	    width: 0.5rem;
>   w-3	    width: 0.75rem;
>   w-4	    width: 1rem;
>   w-5	    width: 1.25rem;
>   w-6	    width: 1.5rem;
>   w-8	    width: 2rem;
>   w-10	width: 2.5rem;
>   w-12	width: 3rem;
>   w-16	width: 4rem;
>   w-20	width: 5rem;
>   w-24	width: 6rem;
>   w-32	width: 8rem;
>   w-40	width: 10rem;
>   w-48	width: 12rem;
>   w-56	width: 14rem;
>   w-64	width: 16rem;
>   w-auto	width: auto;
>   w-px	width: 1px;
>   w-1/2	width: 50%;
>   w-1/3	width: 33.333333%;
>   w-2/3	width: 66.666667%;
>   w-1/4	width: 25%;
>   w-2/4	width: 50%;
>   w-3/4	width: 75%;
>   w-1/5	width: 20%;
>   w-2/5	width: 40%;
>   w-3/5	width: 60%;
>   w-4/5	width: 80%;
>   w-1/6	width: 16.666667%;
>   w-2/6	width: 33.333333%;
>   w-3/6	width: 50%;
>   w-4/6	width: 66.666667%;
>   w-5/6	width: 83.333333%;
>   w-1/12	width: 8.333333%;
>   w-2/12	width: 16.666667%;
>   w-3/12	width: 25%;
>   w-4/12	width: 33.333333%;
>   w-5/12	width: 41.666667%;
>   w-6/12	width: 50%;
>   w-7/12	width: 58.333333%;
>   w-8/12	width: 66.666667%;
>   w-9/12	width: 75%;
>   w-10/12	width: 83.333333%;
>   w-11/12	width: 91.666667%;
>   w-full	width: 100%;
>   w-screen	width: 100vw;

## Min-Width
>   min-w-0	    min-width: 0;
>   min-w-full	min-width: 100%;

## Max-Width
>   max-w-none	max-width: none;
>   max-w-xs	max-width: 20rem;
>   max-w-sm	max-width: 24rem;
>   max-w-md	max-width: 28rem;
>   max-w-lg	max-width: 32rem;
>   max-w-xl	max-width: 36rem;
>   max-w-2xl	max-width: 42rem;
>   max-w-3xl	max-width: 48rem;
>   max-w-4xl	max-width: 56rem;
>   max-w-5xl	max-width: 64rem;
>   max-w-6xl	max-width: 72rem;
>   max-w-full	max-width: 100%;
>   max-w-screen-sm	max-width: 640px;
>   max-w-screen-md	max-width: 768px;
>   max-w-screen-lg	max-width: 1024px;
>   max-w-screen-xl	max-width: 1280px;

## Height
>   h-0	height: 0;
>   h-1	height: 0.25rem;
>   h-2	height: 0.5rem;
>   h-3	height: 0.75rem;
>   h-4	height: 1rem;
>   h-5	height: 1.25rem;
>   h-6	height: 1.5rem;
>   h-8	height: 2rem;
>   h-10	height: 2.5rem;
>   h-12	height: 3rem;
>   h-16	height: 4rem;
>   h-20	height: 5rem;
>   h-24	height: 6rem;
>   h-32	height: 8rem;
>   h-40	height: 10rem;
>   h-48	height: 12rem;
>   h-56	height: 14rem;
>   h-64	height: 16rem;
>   h-auto	height: auto;
>   h-px	height: 1px;
>   h-full	height: 100%;
>   h-screen	height: 100vh;

## Min-Height
>   min-h-0	        min-height: 0;
>   min-h-full  	min-height: 100%;
>   min-h-screen	min-height: 100vh;

## Max-Height
>   max-h-full	max-height: 100%;
>   max-h-screen	max-height: 100vh;

# TYPOGRAPHY
## Font Family
>   font-sans	font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
>   font-serif	font-family: Georgia, Cambria, "Times New Roman", Times, serif;
>   font-mono	font-family: Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;

## Font Size
>   text-xs	font-size: 0.75rem;
>   text-sm	font-size: 0.875rem;
>   text-base	font-size: 1rem;
>   text-lg	font-size: 1.125rem;
>   text-xl	font-size: 1.25rem;
>   text-2xl	font-size: 1.5rem;
>   text-3xl	font-size: 1.875rem;
>   text-4xl	font-size: 2.25rem;
>   text-5xl	font-size: 3rem;
>   text-6xl	font-size: 4rem;

## Font Smoothing
>   antialiased	            -webkit-font-smoothing: antialiased;
>                           -moz-osx-font-smoothing: grayscale;
>   subpixel-antialiased	-webkit-font-smoothing: auto;
>                           -moz-osx-font-smoothing: auto;

## Font Style
>   italic	font-style: italic;
>   not-italic	font-style: normal;

## Font Weight
>   font-hairline	font-weight: 100;
>   font-thin	font-weight: 200;
>   font-light	font-weight: 300;
>   font-normal	font-weight: 400;
>   font-medium	font-weight: 500;
>   font-semibold	font-weight: 600;
>   font-bold	font-weight: 700;
>   font-extrabold	font-weight: 800;
>   font-black	font-weight: 900;

## Font Variant Numeric
>   normal-nums	font-variant-numeric: normal;
>   ordinal	font-variant-numeric: ordinal;
>   slashed-zero	font-variant-numeric: slashed-zero;
>   lining-nums	font-variant-numeric: lining-nums;
>   oldstyle-nums	font-variant-numeric: oldstyle-nums;
>   proportional-nums	font-variant-numeric: proportional-nums;
>   tabular-nums	font-variant-numeric: tabular-nums;
>   diagonal-fractions	font-variant-numeric: diagonal-fractions;
>   stacked-fractions	font-variant-numeric: stacked-fractions;

## Letter Spacing
>   tracking-tighter	letter-spacing: -0.05em;
>   tracking-tight	letter-spacing: -0.025em;
>   tracking-normal	letter-spacing: 0;
>   tracking-wide	letter-spacing: 0.025em;
>   tracking-wider	letter-spacing: 0.05em;
>   tracking-widest	letter-spacing: 0.1em;

## Line Height
>   leading-3	line-height: .75rem;
>   leading-4	line-height: 1rem;
>   leading-5	line-height: 1.25rem;
>   leading-6	line-height: 1.5rem;
>   leading-7	line-height: 1.75rem;
>   leading-8	line-height: 2rem;
>   leading-9	line-height: 2.25rem;
>   leading-10	line-height: 2.5rem;
>   leading-none	line-height: 1;
>   leading-tight	line-height: 1.25;
>   leading-snug	line-height: 1.375;
>   leading-normal	line-height: 1.5;
>   leading-relaxed	line-height: 1.625;
>   leading-loose	line-height: 2;

## List Style Type
>   list-none	list-style-type: none;
>   list-disc	list-style-type: disc;
>   list-decimal	list-style-type: decimal;

## List Style Position
>   list-inside	list-style-position: inside;
>   list-outside	list-style-position: outside;

## Placeholder Color
>   placeholder-transparent::placeholder	color: transparent;	Aa
>   placeholder-current::placeholder	color: currentColor;	Aa
>   placeholder-black::placeholder	color: #000;	Aa
>   placeholder-white::placeholder	color: #fff;	Aa
>   placeholder-gray-100::placeholder	color: #f7fafc;	Aa
>   placeholder-gray-200::placeholder	color: #edf2f7;	Aa
>   placeholder-gray-300::placeholder	color: #e2e8f0;	Aa
>   placeholder-gray-400::placeholder	color: #cbd5e0;	Aa
>   placeholder-gray-500::placeholder	color: #a0aec0;	Aa
>   placeholder-gray-600::placeholder	color: #718096;	Aa
>   placeholder-gray-700::placeholder	color: #4a5568;	Aa
>   placeholder-gray-800::placeholder	color: #2d3748;	Aa
>   placeholder-gray-900::placeholder	color: #1a202c;	Aa
>   placeholder-red-100::placeholder	color: #fff5f5;	Aa
>   placeholder-red-200::placeholder	color: #fed7d7;	Aa
>   placeholder-red-300::placeholder	color: #feb2b2;	Aa
>   placeholder-red-400::placeholder	color: #fc8181;	Aa
>   placeholder-red-500::placeholder	color: #f56565;	Aa
>   placeholder-red-600::placeholder	color: #e53e3e;	Aa
>   placeholder-red-700::placeholder	color: #c53030;	Aa
>   placeholder-red-800::placeholder	color: #9b2c2c;	Aa
>   placeholder-red-900::placeholder	color: #742a2a;	Aa
>   placeholder-orange-100::placeholder	color: #fffaf0;	Aa
>   placeholder-orange-200::placeholder	color: #feebc8;	Aa
>   placeholder-orange-300::placeholder	color: #fbd38d;	Aa
>   placeholder-orange-400::placeholder	color: #f6ad55;	Aa
>   placeholder-orange-500::placeholder	color: #ed8936;	Aa
>   placeholder-orange-600::placeholder	color: #dd6b20;	Aa
>   placeholder-orange-700::placeholder	color: #c05621;	Aa
>   placeholder-orange-800::placeholder	color: #9c4221;	Aa
>   placeholder-orange-900::placeholder	color: #7b341e;	Aa
>   placeholder-yellow-100::placeholder	color: #fffff0;	Aa
>   placeholder-yellow-200::placeholder	color: #fefcbf;	Aa
>   placeholder-yellow-300::placeholder	color: #faf089;	Aa
>   placeholder-yellow-400::placeholder	color: #f6e05e;	Aa
>   placeholder-yellow-500::placeholder	color: #ecc94b;	Aa
>   placeholder-yellow-600::placeholder	color: #d69e2e;	Aa
>   placeholder-yellow-700::placeholder	color: #b7791f;	Aa
>   placeholder-yellow-800::placeholder	color: #975a16;	Aa
>   placeholder-yellow-900::placeholder	color: #744210;	Aa
>   placeholder-green-100::placeholder	color: #f0fff4;	Aa
>   placeholder-green-200::placeholder	color: #c6f6d5;	Aa
>   placeholder-green-300::placeholder	color: #9ae6b4;	Aa
>   placeholder-green-400::placeholder	color: #68d391;	Aa
>   placeholder-green-500::placeholder	color: #48bb78;	Aa
>   placeholder-green-600::placeholder	color: #38a169;	Aa
>   placeholder-green-700::placeholder	color: #2f855a;	Aa
>   placeholder-green-800::placeholder	color: #276749;	Aa
>   placeholder-green-900::placeholder	color: #22543d;	Aa
>   placeholder-teal-100::placeholder	color: #e6fffa;	Aa
>   placeholder-teal-200::placeholder	color: #b2f5ea;	Aa
>   placeholder-teal-300::placeholder	color: #81e6d9;	Aa
>   placeholder-teal-400::placeholder	color: #4fd1c5;	Aa
>   placeholder-teal-500::placeholder	color: #38b2ac;	Aa
>   placeholder-teal-600::placeholder	color: #319795;	Aa
>   placeholder-teal-700::placeholder	color: #2c7a7b;	Aa
>   placeholder-teal-800::placeholder	color: #285e61;	Aa
>   placeholder-teal-900::placeholder	color: #234e52;	Aa
>   placeholder-blue-100::placeholder	color: #ebf8ff;	Aa
>   placeholder-blue-200::placeholder	color: #bee3f8;	Aa
>   placeholder-blue-300::placeholder	color: #90cdf4;	Aa
>   placeholder-blue-400::placeholder	color: #63b3ed;	Aa
>   placeholder-blue-500::placeholder	color: #4299e1;	Aa
>   placeholder-blue-600::placeholder	color: #3182ce;	Aa
>   placeholder-blue-700::placeholder	color: #2b6cb0;	Aa
>   placeholder-blue-800::placeholder	color: #2c5282;	Aa
>   placeholder-blue-900::placeholder	color: #2a4365;	Aa
>   placeholder-indigo-100::placeholder	color: #ebf4ff;	Aa
>   placeholder-indigo-200::placeholder	color: #c3dafe;	Aa
>   placeholder-indigo-300::placeholder	color: #a3bffa;	Aa
>   placeholder-indigo-400::placeholder	color: #7f9cf5;	Aa
>   placeholder-indigo-500::placeholder	color: #667eea;	Aa
>   placeholder-indigo-600::placeholder	color: #5a67d8;	Aa
>   placeholder-indigo-700::placeholder	color: #4c51bf;	Aa
>   placeholder-indigo-800::placeholder	color: #434190;	Aa
>   placeholder-indigo-900::placeholder	color: #3c366b;	Aa
>   placeholder-purple-100::placeholder	color: #faf5ff;	Aa
>   placeholder-purple-200::placeholder	color: #e9d8fd;	Aa
>   placeholder-purple-300::placeholder	color: #d6bcfa;	Aa
>   placeholder-purple-400::placeholder	color: #b794f4;	Aa
>   placeholder-purple-500::placeholder	color: #9f7aea;	Aa
>   placeholder-purple-600::placeholder	color: #805ad5;	Aa
>   placeholder-purple-700::placeholder	color: #6b46c1;	Aa
>   placeholder-purple-800::placeholder	color: #553c9a;	Aa
>   placeholder-purple-900::placeholder	color: #44337a;	Aa
>   placeholder-pink-100::placeholder	color: #fff5f7;	Aa
>   placeholder-pink-200::placeholder	color: #fed7e2;	Aa
>   placeholder-pink-300::placeholder	color: #fbb6ce;	Aa
>   placeholder-pink-400::placeholder	color: #f687b3;	Aa
>   placeholder-pink-500::placeholder	color: #ed64a6;	Aa
>   placeholder-pink-600::placeholder	color: #d53f8c;	Aa
>   placeholder-pink-700::placeholder	color: #b83280;	Aa
>   placeholder-pink-800::placeholder	color: #97266d;	Aa
>   placeholder-pink-900::placeholder	color: #702459;	Aa

## Placeholder Opacity
>   placeholder-opacity-0	--placeholder-opacity: 0;
>   placeholder-opacity-25	--placeholder-opacity: 0.25;
>   placeholder-opacity-50	--placeholder-opacity: 0.5;
>   placeholder-opacity-75	--placeholder-opacity: 0.75;
>   placeholder-opacity-100	--placeholder-opacity: 1;

## Text Align
>   text-left	text-align: left;
>   text-center	text-align: center;
>   text-right	text-align: right;
>   text-justify	text-align: justify;

## Text Color
>   text-transparent	color: transparent;	Aa
>   text-current	color: currentColor;	Aa
>   text-black	color: #000;	Aa
>   text-white	color: #fff;	Aa
>   text-gray-100	color: #f7fafc;	Aa
>   text-gray-200	color: #edf2f7;	Aa
>   text-gray-300	color: #e2e8f0;	Aa
>   text-gray-400	color: #cbd5e0;	Aa
>   text-gray-500	color: #a0aec0;	Aa
>   text-gray-600	color: #718096;	Aa
>   text-gray-700	color: #4a5568;	Aa
>   text-gray-800	color: #2d3748;	Aa
>   text-gray-900	color: #1a202c;	Aa
>   text-red-100	color: #fff5f5;	Aa
>   text-red-200	color: #fed7d7;	Aa
>   text-red-300	color: #feb2b2;	Aa
>   text-red-400	color: #fc8181;	Aa
>   text-red-500	color: #f56565;	Aa
>   text-red-600	color: #e53e3e;	Aa
>   text-red-700	color: #c53030;	Aa
>   text-red-800	color: #9b2c2c;	Aa
>   text-red-900	color: #742a2a;	Aa
>   text-orange-100	color: #fffaf0;	Aa
>   text-orange-200	color: #feebc8;	Aa
>   text-orange-300	color: #fbd38d;	Aa
>   text-orange-400	color: #f6ad55;	Aa
>   text-orange-500	color: #ed8936;	Aa
>   text-orange-600	color: #dd6b20;	Aa
>   text-orange-700	color: #c05621;	Aa
>   text-orange-800	color: #9c4221;	Aa
>   text-orange-900	color: #7b341e;	Aa
>   text-yellow-100	color: #fffff0;	Aa
>   text-yellow-200	color: #fefcbf;	Aa
>   text-yellow-300	color: #faf089;	Aa
>   text-yellow-400	color: #f6e05e;	Aa
>   text-yellow-500	color: #ecc94b;	Aa
>   text-yellow-600	color: #d69e2e;	Aa
>   text-yellow-700	color: #b7791f;	Aa
>   text-yellow-800	color: #975a16;	Aa
>   text-yellow-900	color: #744210;	Aa
>   text-green-100	color: #f0fff4;	Aa
>   text-green-200	color: #c6f6d5;	Aa
>   text-green-300	color: #9ae6b4;	Aa
>   text-green-400	color: #68d391;	Aa
>   text-green-500	color: #48bb78;	Aa
>   text-green-600	color: #38a169;	Aa
>   text-green-700	color: #2f855a;	Aa
>   text-green-800	color: #276749;	Aa
>   text-green-900	color: #22543d;	Aa
>   text-teal-100	color: #e6fffa;	Aa
>   text-teal-200	color: #b2f5ea;	Aa
>   text-teal-300	color: #81e6d9;	Aa
>   text-teal-400	color: #4fd1c5;	Aa
>   text-teal-500	color: #38b2ac;	Aa
>   text-teal-600	color: #319795;	Aa
>   text-teal-700	color: #2c7a7b;	Aa
>   text-teal-800	color: #285e61;	Aa
>   text-teal-900	color: #234e52;	Aa
>   text-blue-100	color: #ebf8ff;	Aa
>   text-blue-200	color: #bee3f8;	Aa
>   text-blue-300	color: #90cdf4;	Aa
>   text-blue-400	color: #63b3ed;	Aa
>   text-blue-500	color: #4299e1;	Aa
>   text-blue-600	color: #3182ce;	Aa
>   text-blue-700	color: #2b6cb0;	Aa
>   text-blue-800	color: #2c5282;	Aa
>   text-blue-900	color: #2a4365;	Aa
>   text-indigo-100	color: #ebf4ff;	Aa
>   text-indigo-200	color: #c3dafe;	Aa
>   text-indigo-300	color: #a3bffa;	Aa
>   text-indigo-400	color: #7f9cf5;	Aa
>   text-indigo-500	color: #667eea;	Aa
>   text-indigo-600	color: #5a67d8;	Aa
>   text-indigo-700	color: #4c51bf;	Aa
>   text-indigo-800	color: #434190;	Aa
>   text-indigo-900	color: #3c366b;	Aa
>   text-purple-100	color: #faf5ff;	Aa
>   text-purple-200	color: #e9d8fd;	Aa
>   text-purple-300	color: #d6bcfa;	Aa
>   text-purple-400	color: #b794f4;	Aa
>   text-purple-500	color: #9f7aea;	Aa
>   text-purple-600	color: #805ad5;	Aa
>   text-purple-700	color: #6b46c1;	Aa
>   text-purple-800	color: #553c9a;	Aa
>   text-purple-900	color: #44337a;	Aa
>   text-pink-100	color: #fff5f7;	Aa
>   text-pink-200	color: #fed7e2;	Aa
>   text-pink-300	color: #fbb6ce;	Aa
>   text-pink-400	color: #f687b3;	Aa
>   text-pink-500	color: #ed64a6;	Aa
>   text-pink-600	color: #d53f8c;	Aa
>   text-pink-700	color: #b83280;	Aa
>   text-pink-800	color: #97266d;	Aa
>   text-pink-900	color: #702459;	Aa

## Text Opacity
>   text-opacity-0	--text-opacity: 0;
>   text-opacity-25	--text-opacity: 0.25;
>   text-opacity-50	--text-opacity: 0.5;
>   text-opacity-75	--text-opacity: 0.75;
>   text-opacity-100	--text-opacity: 1;

## Text Decoration
>   underline	text-decoration: underline;
>   line-through	text-decoration: line-through;
>   no-underline	text-decoration: none;

## Text Transform
>   uppercase	text-transform: uppercase;
>   lowercase	text-transform: lowercase;
>   capitalize	text-transform: capitalize;
>   normal-case	text-transform: none;

## Vertical Align
>   align-baseline	vertical-align: baseline;
>   align-top	vertical-align: top;
>   align-middle	vertical-align: middle;
>   align-bottom	vertical-align: bottom;
>   align-text-top	vertical-align: text-top;
>   align-text-bottom	vertical-align: text-bottom;

## Whitespace
>   whitespace-normal	white-space: normal;
>   whitespace-no-wrap	white-space: nowrap;
>   whitespace-pre	white-space: pre;
>   whitespace-pre-line	white-space: pre-line;
>   whitespace-pre-wrap	white-space: pre-wrap;

## Word Break
>   break-normal	overflow-wrap: normal;
>                   word-break: normal;
>   break-words	    overflow-wrap: break-word;
>   break-all	    word-break: break-all;
>   truncate	    overflow: hidden;
>                   text-overflow: ellipsis;
>                   white-space: nowrap;

# TABLES
## Border Collapse
>   border-collapse	border-collapse: collapse;
>   border-separate	border-collapse: separate;

## Table Layout
>   table-auto	table-layout: auto;
>   table-fixed	table-layout: fixed;

# TRANSITIONS AND ANIMATION
## Transition Property
>   transition-none	transition-property: none;
>   transition-all	transition-property: all;
>   transition	transition-property: background-color, border-color, color, fill, stroke, opacity, box-shadow, transform;
>   transition-colors	transition-property: background-color, border-color, color, fill, stroke;
>   transition-opacity	transition-property: opacity;
>   transition-shadow	transition-property: box-shadow;
>   transition-transform	transition-property: transform;

## Transition Duration
>   duration-75	transition-duration: 75ms;
>   duration-100	transition-duration: 100ms;
>   duration-150	transition-duration: 150ms;
>   duration-200	transition-duration: 200ms;
>   duration-300	transition-duration: 300ms;
>   duration-500	transition-duration: 500ms;
>   duration-700	transition-duration: 700ms;
>   duration-1000	transition-duration: 1000ms;

## Transition Timing Function
>   ease-linear	transition-timing-function: linear;
>   ease-in	transition-timing-function: cubic-bezier(0.4, 0, 1, 1);
>   ease-out	transition-timing-function: cubic-bezier(0, 0, 0.2, 1);
>   ease-in-out	transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);

## Transition Delay
>   delay-75	transition-delay: 75ms;
>   delay-100	transition-delay: 100ms;
>   delay-150	transition-delay: 150ms;
>   delay-200	transition-delay: 200ms;
>   delay-300	transition-delay: 300ms;
>   delay-500	transition-delay: 500ms;
>   delay-700	transition-delay: 700ms;
>   delay-1000	transition-delay: 1000ms;

## Animation
>   animate-none	animation: none;
>   animate-spin	animation: spin 1s linear infinite;

@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
>   animate-ping	animation: ping 1s cubic-bezier(0, 0, 0.2, 1) infinite;

@keyframes ping {
  0% {
    transform: scale(1);
    opacity: 1;
  }
  75%, 100% {
    transform: scale(2);
    opacity: 0;
  }
}
>   animate-pulse	animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;

@keyframes pulse {
  0%, 100% {
    opacity: 1;
  }
  50% {
    opacity: .5;
  }
}
>   animate-bounce	animation: bounce 1s infinite;

@keyframes bounce {
  0%, 100% {
    transform: translateY(-25%);
    animationTimingFunction: cubic-bezier(0.8, 0, 1, 1);
  }
  50% {
    transform: translateY(0);
    animationTimingFunction: cubic-bezier(0, 0, 0.2, 1);
  }
}

# TRANSFORMS
## Scale
>   scale-0	    --transform-scale-x: 0;
>               --transform-scale-y: 0;
>   scale-50	--transform-scale-x: .5;
>               --transform-scale-y: .5;
>   scale-75	--transform-scale-x: .75;
>               --transform-scale-y: .75;
>   scale-90	--transform-scale-x: .9;
>               --transform-scale-y: .9;
>   scale-95	--transform-scale-x: .95;
>               --transform-scale-y: .95;
>   scale-100	--transform-scale-x: 1;
>               --transform-scale-y: 1;
>   scale-105	--transform-scale-x: 1.05;
>               --transform-scale-y: 1.05;
>   scale-110	--transform-scale-x: 1.1;
>               --transform-scale-y: 1.1;
>   scale-125	--transform-scale-x: 1.25;
>               --transform-scale-y: 1.25;
>   scale-150	--transform-scale-x: 1.5;
>               --transform-scale-y: 1.5;
>   scale-x-0	--transform-scale-x: 0;
>   scale-x-50	--transform-scale-x: .5;
>   scale-x-75	--transform-scale-x: .75;
>   scale-x-90	--transform-scale-x: .9;
>   scale-x-95	--transform-scale-x: .95;
>   scale-x-100	--transform-scale-x: 1;
>   scale-x-105	--transform-scale-x: 1.05;
>   scale-x-110	--transform-scale-x: 1.1;
>   scale-x-125	--transform-scale-x: 1.25;
>   scale-x-150	--transform-scale-x: 1.5;
>   scale-y-0	--transform-scale-y: 0;
>   scale-y-50	--transform-scale-y: .5;
>   scale-y-75	--transform-scale-y: .75;
>   scale-y-90	--transform-scale-y: .9;
>   scale-y-95	--transform-scale-y: .95;
>   scale-y-100	--transform-scale-y: 1;
>   scale-y-105	--transform-scale-y: 1.05;
>   scale-y-110	--transform-scale-y: 1.1;
>   scale-y-125	--transform-scale-y: 1.25;
>   scale-y-150	--transform-scale-y: 1.5;

## Rotate
>   rotate-0	--transform-rotate: 0;
>   rotate-45	--transform-rotate: 45deg;
>   rotate-90	--transform-rotate: 90deg;
>   rotate-180	--transform-rotate: 180deg;
>   -rotate-180	--transform-rotate: -180deg;
>   -rotate-90	--transform-rotate: -90deg;
>   -rotate-45	--transform-rotate: -45deg;

## Translate
>   translate-x-0	--transform-translate-x: 0;
>   translate-x-1	--transform-translate-x: 0.25rem;
>   translate-x-2	--transform-translate-x: 0.5rem;
>   translate-x-3	--transform-translate-x: 0.75rem;
>   translate-x-4	--transform-translate-x: 1rem;
>   translate-x-5	--transform-translate-x: 1.25rem;
>   translate-x-6	--transform-translate-x: 1.5rem;
>   translate-x-8	--transform-translate-x: 2rem;
>   translate-x-10	--transform-translate-x: 2.5rem;
>   translate-x-12	--transform-translate-x: 3rem;
>   translate-x-16	--transform-translate-x: 4rem;
>   translate-x-20	--transform-translate-x: 5rem;
>   translate-x-24	--transform-translate-x: 6rem;
>   translate-x-32	--transform-translate-x: 8rem;
>   translate-x-40	--transform-translate-x: 10rem;
>   translate-x-48	--transform-translate-x: 12rem;
>   translate-x-56	--transform-translate-x: 14rem;
>   translate-x-64	--transform-translate-x: 16rem;
>   translate-x-px	--transform-translate-x: 1px;
>   -translate-x-1	--transform-translate-x: -0.25rem;
>   -translate-x-2	--transform-translate-x: -0.5rem;
>   -translate-x-3	--transform-translate-x: -0.75rem;
>   -translate-x-4	--transform-translate-x: -1rem;
>   -translate-x-5	--transform-translate-x: -1.25rem;
>   -translate-x-6	--transform-translate-x: -1.5rem;
>   -translate-x-8	--transform-translate-x: -2rem;
>   -translate-x-10	--transform-translate-x: -2.5rem;
>   -translate-x-12	--transform-translate-x: -3rem;
>   -translate-x-16	--transform-translate-x: -4rem;
>   -translate-x-20	--transform-translate-x: -5rem;
>   -translate-x-24	--transform-translate-x: -6rem;
>   -translate-x-32	--transform-translate-x: -8rem;
>   -translate-x-40	--transform-translate-x: -10rem;
>   -translate-x-48	--transform-translate-x: -12rem;
>   -translate-x-56	--transform-translate-x: -14rem;
>   -translate-x-64	--transform-translate-x: -16rem;
>   -translate-x-px	--transform-translate-x: -1px;
>   -translate-x-full	--transform-translate-x: -100%;
>   -translate-x-1/2	--transform-translate-x: -50%;
>   translate-x-1/2	--transform-translate-x: 50%;
>   translate-x-full	--transform-translate-x: 100%;
>   translate-y-0	--transform-translate-y: 0;
>   translate-y-1	--transform-translate-y: 0.25rem;
>   translate-y-2	--transform-translate-y: 0.5rem;
>   translate-y-3	--transform-translate-y: 0.75rem;
>   translate-y-4	--transform-translate-y: 1rem;
>   translate-y-5	--transform-translate-y: 1.25rem;
>   translate-y-6	--transform-translate-y: 1.5rem;
>   translate-y-8	--transform-translate-y: 2rem;
>   translate-y-10	--transform-translate-y: 2.5rem;
>   translate-y-12	--transform-translate-y: 3rem;
>   translate-y-16	--transform-translate-y: 4rem;
>   translate-y-20	--transform-translate-y: 5rem;
>   translate-y-24	--transform-translate-y: 6rem;
>   translate-y-32	--transform-translate-y: 8rem;
>   translate-y-40	--transform-translate-y: 10rem;
>   translate-y-48	--transform-translate-y: 12rem;
>   translate-y-56	--transform-translate-y: 14rem;
>   translate-y-64	--transform-translate-y: 16rem;
>   translate-y-px	--transform-translate-y: 1px;
>   -translate-y-1	--transform-translate-y: -0.25rem;
>   -translate-y-2	--transform-translate-y: -0.5rem;
>   -translate-y-3	--transform-translate-y: -0.75rem;
>   -translate-y-4	--transform-translate-y: -1rem;
>   -translate-y-5	--transform-translate-y: -1.25rem;
>   -translate-y-6	--transform-translate-y: -1.5rem;
>   -translate-y-8	--transform-translate-y: -2rem;
>   -translate-y-10	--transform-translate-y: -2.5rem;
>   -translate-y-12	--transform-translate-y: -3rem;
>   -translate-y-16	--transform-translate-y: -4rem;
>   -translate-y-20	--transform-translate-y: -5rem;
>   -translate-y-24	--transform-translate-y: -6rem;
>   -translate-y-32	--transform-translate-y: -8rem;
>   -translate-y-40	--transform-translate-y: -10rem;
>   -translate-y-48	--transform-translate-y: -12rem;
>   -translate-y-56	--transform-translate-y: -14rem;
>   -translate-y-64	--transform-translate-y: -16rem;
>   -translate-y-px	--transform-translate-y: -1px;
>   -translate-y-full	--transform-translate-y: -100%;
>   -translate-y-1/2	--transform-translate-y: -50%;
>   translate-y-1/2	--transform-translate-y: 50%;
>   translate-y-full	--transform-translate-y: 100%;

## Skew
>   skew-x-0	--transform-skew-x: 0;
>   skew-x-3	--transform-skew-x: 3deg;
>   skew-x-6	--transform-skew-x: 6deg;
>   skew-x-12	--transform-skew-x: 12deg;
>   -skew-x-12	--transform-skew-x: -12deg;
>   -skew-x-6	--transform-skew-x: -6deg;
>   -skew-x-3	--transform-skew-x: -3deg;
>   skew-y-0	--transform-skew-y: 0;
>   skew-y-3	--transform-skew-y: 3deg;
>   skew-y-6	--transform-skew-y: 6deg;
>   skew-y-12	--transform-skew-y: 12deg;
>   -skew-y-12	--transform-skew-y: -12deg;
>   -skew-y-6	--transform-skew-y: -6deg;
>   -skew-y-3	--transform-skew-y: -3deg;

## Transform Origin
>   origin-center	transform-origin: center;
>   origin-top	transform-origin: top;
>   origin-top-right	transform-origin: top right;
>   origin-right	transform-origin: right;
>   origin-bottom-right	transform-origin: bottom right;
>   origin-bottom	transform-origin: bottom;
>   origin-bottom-left	transform-origin: bottom left;
>   origin-left	transform-origin: left;
>   origin-top-left	transform-origin: top left;

# INTERACTIVITY
## Appearance
>   appearance-none	appearance: none;

## Cursor
>   cursor-auto	cursor: auto;
>   cursor-default	cursor: default;
>   cursor-pointer	cursor: pointer;
>   cursor-wait	cursor: wait;
>   cursor-text	cursor: text;
>   cursor-move	cursor: move;
>   cursor-not-allowed	cursor: not-allowed;

## Outline
>   outline-none	outline: 0;

## Pointer Events
>   pointer-events-none	pointer-events: none;
>   pointer-events-auto	pointer-events: auto;

## Resize
>   resize-none	resize: none;
>   resize-y	resize: vertical;
>   resize-x	resize: horizontal;
>   resize	resize: both;

## User Select
>   select-none	user-select: none;
>   select-text	user-select: text;
>   select-all	user-select: all;
>   select-auto	user-select: auto;

# SVG
## Fill
>   fill-current	fill: currentColor;

## Stroke
>   stroke-current	stroke: currentColor;

## Stroke Width
>   stroke-0	stroke-width: 0;
>   stroke-1	stroke-width: 1;
>   stroke-2	stroke-width: 2;

# NOT THAT USED
## Box Sizing
>   box-border	box-sizing: border-box;
>   box-content	box-sizing: content-box;

## Overflow
>   overflow-auto	overflow: auto;
>   overflow-hidden	overflow: hidden;
>   overflow-visible	overflow: visible;
>   overflow-scroll	overflow: scroll;
>   overflow-x-auto	overflow-x: auto;
>   overflow-y-auto	overflow-y: auto;
>   overflow-x-hidden	overflow-x: hidden;
>   overflow-y-hidden	overflow-y: hidden;
>   overflow-x-visible	overflow-x: visible;
>   overflow-y-visible	overflow-y: visible;
>   overflow-x-scroll	overflow-x: scroll;
>   overflow-y-scroll	overflow-y: scroll;
>   scrolling-touch	-webkit-overflow-scrolling: touch;
>   scrolling-auto	-webkit-overflow-scrolling: auto;

## Overscroll Behavior
>   overscroll-auto	overscroll-behavior: auto;
>   overscroll-contain	overscroll-behavior: contain;
>   overscroll-none	overscroll-behavior: none;
>   overscroll-y-auto	overscroll-behavior-y: auto;
>   overscroll-y-contain	overscroll-behavior-y: contain;
>   overscroll-y-none	overscroll-behavior-y: none;
>   overscroll-x-auto	overscroll-behavior-x: auto;
>   overscroll-x-contain	overscroll-behavior-x: contain;
>   overscroll-x-none	overscroll-behavior-x: none;


## ACCESSIBILITY
## Screen Readers
.sr-only	position: absolute;
width: 1px;
height: 1px;
padding: 0;
margin: -1px;
overflow: hidden;
clip: rect(0, 0, 0, 0);
white-space: nowrap;
border-width: 0;
.not-sr-only	position: static;
width: auto;
height: auto;
padding: 0;
margin: 0;
overflow: visible;
clip: auto;
white-space: normal;