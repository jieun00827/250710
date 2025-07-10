<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🌐 국제공동수업 기획 가이드</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Pretendard:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Pretendard', sans-serif;
            color: #1a202c; /* 군청색 */
        }
        .text-dark-blue {
            color: #1a202c;
        }
        .bg-light-orange {
            background-color: #FFF7ED; /* Tailwind orange-50 */
        }
        .bg-medium-orange {
            background-color: #FED7AA; /* Tailwind orange-200 */
        }
        .bg-light-teal {
            background-color: #ECFDF5; /* Tailwind teal-50 */
        }
        .bg-medium-teal {
            background-color: #A7F3D0; /* Tailwind teal-200 */
        }
        .bg-light-sky {
            background-color: #F0F9FF; /* Tailwind sky-50 */
        }
        .bg-medium-sky {
            background-color: #BAE6FD; /* Tailwind sky-200 */
        }
        .sticky-nav {
            position: sticky;
            top: 0;
            z-index: 50;
        }
        .hover-highlight:hover {
            background-color: #F3F4F6;
        }
        .accordion-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-out;
        }
        .accordion-content.active {
            max-height: 500px; /* Adjust as needed */
            transition: max-height 0.5s ease-in;
        }
    </style>
</head>
<body class="bg-gray-50">

    <nav class="sticky-nav bg-white shadow-md p-4 flex justify-between items-center">
        <div class="flex items-center">
            <span class="text-2xl font-bold text-dark-blue mr-2">🌐 국제공동수업 가이드</span>
        </div>
        <ul class="flex space-x-6 text-dark-blue text-sm font-semibold">
            <li><a href="#intro" class="hover:text-blue-600 flex items-center"><span class="mr-1">✨</span>서론</a></li>
            <li><a href="#initial-planning" class="hover:text-blue-600 flex items-center"><span class="mr-1">🤝</span>초기 협의</a></li>
            <li><a href="#operation-planning" class="hover:text-blue-600 flex items-center"><span class="mr-1">🗓️</span>운영 기획</a></li>
            <li><a href="#edutech" class="hover:text-blue-
