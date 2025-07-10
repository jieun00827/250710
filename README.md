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
            <li><a href="#edutech" class="hover:text-blue-600 flex items-center"><span class="mr-1">💻</span>에듀테크 활용</a></li>
        </ul>
    </nav>

    <div class="container mx-auto px-4 py-8 max-w-4xl">
        <header id="intro" class="text-center mb-12">
            <h1 class="text-5xl font-extrabold text-dark-blue mb-4 leading-tight">
                수업 사례로 만나는, <br class="md:hidden">에듀테크 활용 초등 국제공동수업 <br class="md:hidden">
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-teal-500 to-sky-500">국제공동수업 기획</span>
            </h1>
            <p class="text-xl text-gray-700 max-w-2xl mx-auto">
                국제공동수업이란?  세계 각국의 학생들과 온/오프라인 공간에서 함께 만나 언어와 문화를 배우는 한국-해외학교 간 수업 교류 프로그램
            </p>
            <div class="mt-8">
                <img src="https://via.placeholder.com/600x300?text=Global+Collaboration+Illustration" alt="학생들이 함께 공부하는 모습" class="rounded-lg shadow-lg mx-auto">
            </div>
        </header>

        <section id="initial-planning" class="mb-16">
            <h2 class="text-4xl font-bold text-dark-blue mb-8 flex items-center">
                <span class="mr-3 text-yellow-500">🤝</span>1. 수업 운영 계획 초기 협의
            </h2>
            <p class="text-lg mb-8 text-gray-700 leading-relaxed">
                국제공동수업의 성공적인 시작을 위해 해외 교사와의 긴밀한 협의는 필수적입니다.
            </p>

            <div class="grid md:grid-cols-2 gap-8">
                <div class="bg-light-orange p-6 rounded-lg shadow-md border-l-4 border-orange-500">
                    <h3 class="text-2xl font-semibold text-orange-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🔗</span> 상대 학교 매칭
                    </h3>
                    <ul class="list-none space-y-2 text-gray-800">
                        <li class="flex items-start"><span class="text-orange-500 mr-2 mt-1">✅</span> <strong>교육청 매칭:</strong> MOU 체결로 안정적이고 편리합니다.</li>
                        <li class="flex items-start"><span class="text-orange-500 mr-2 mt-1">⚠️</span> <strong>직접 매칭:</strong> ISNet/Epals, 이메일/SNS (회신 없을 수 있음, 증빙 서류 요청 가능)</li>
                        <li class="flex items-start"><span class="text-orange-500 mr-2 mt-1">📝</span> <strong>첫 이메일:</strong> 교육관, 비전, 수업 콘텐츠, 국제 수업 이력 등 상세 기재</li>
                    </ul>
                </div>

                <div class="bg-light-sky p-6 rounded-lg shadow-md border-l-4 border-sky-500">
                    <h3 class="text-2xl font-semibold text-sky-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">👨‍👩‍👧‍👦</span> 학생 및 학부모 안내
                    </h3>
                    <ul class="list-none space-y-2 text-gray-800">
                        <li class="flex items-start"><span class="text-sky-500 mr-2 mt-1">✅</span> 국제공동수업의 목적과 진행 방식 설명</li>
                        <li class="flex items-start"><span class="text-sky-500 mr-2 mt-1">📄</span> <strong>필수:</strong> 개인정보 및 초상권 수집 이용 동의서 확보</li>
                    </ul>
                </div>

                <div class="bg-light-teal p-6 rounded-lg shadow-md border-l-4 border-teal-500">
                    <h3 class="text-2xl font-semibold text-teal-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">📞</span> 해외 교사와의 연락 수단
                    </h3>
                    <ul class="list-none space-y-2 text-gray-800">
                        <li class="flex items-start"><span class="text-teal-500 mr-2 mt-1">🗣️</span> <strong>주요 도구:</strong> Zoom/Google Meet, Facebook 메신저, WhatsApp</li>
                        <li class="flex items-start"><span class="text-teal-500 mr-2 mt-1">💡</span> <strong>팁:</strong> 나라별 선호하는 SNS가 다름을 인지하고 유연하게 대처</li>
                    </ul>
                </div>

                <div class="bg-light-orange p-6 rounded-lg shadow-md border-l-4 border-orange-500">
                    <h3 class="text-2xl font-semibold text-orange-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🎯</span> 프로젝트 기획
                    </h3>
                    <ul class="list-none space-y-2 text-gray-800">
                        <li class="flex items-start"><span class="text-orange-500 mr-2 mt-1">📝</span> 프로젝트 주제 선정 및 운영 방법/내용 사전 협의</li>
                    </ul>
                </div>
            </div>

            <div class="bg-medium-sky p-6 rounded-lg shadow-lg border-l-4 border-blue-500 mt-8">
                <h3 class="text-2xl font-semibold text-blue-800 mb-3 flex items-center">
                    <span class="mr-2 text-3xl">💻</span> 학급 디지털 환경 기본 준비
                </h3>
                <div class="grid md:grid-cols-2 gap-4 text-gray-800">
                    <ul class="list-none space-y-2">
                        <li class="flex items-center"><span class="text-blue-600 mr-2">✅</span> 1인 1 태블릿 또는 노트북</li>
                        <li class="flex items-center"><span class="text-blue-600 mr-2">✅</span> 대형 스크린 (교실 TV)</li>
                        <li class="flex items-center"><span class="text-blue-600 mr-2">✅</span> 스마트폰 광각 렌즈</li>
                        <li class="flex items-center"><span class="text-blue-600 mr-2">✅</span> 학생 이어폰/헤드셋</li>
                    </ul>
                    <ul class="list-none space-y-2">
                        <li class="flex items-center"><span class="text-blue-600 mr-2">✅</span> 교사의 유료 Zoom 계정 (시간 제한 없음)</li>
                        <li class="flex items-center"><span class="text-blue-600 mr-2">✅</span> 비실시간 온라인 플랫폼 및 에듀테크 수업을 위한 학생 구글 계정 (학생 Zoom 계정 불필요)</li>
                        <li class="flex items-center"><span class="text-blue-600 mr-2">✨</span> <strong>추천:</strong> Padlet 연간 이용권</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="operation-planning" class="mb-16">
            <h2 class="text-4xl font-bold text-dark-blue mb-8 flex items-center">
                <span class="mr-3 text-orange-500">🗓️</span>2. 국제 공동 수업 운영 기획 방법
            </h2>
            <p class="text-lg mb-8 text-gray-700 leading-relaxed">
                수업 기획 시 가장 중요한 것은 명확한 <strong>방향성 설정</strong>입니다.
            </p>

            <div class="bg-medium-orange p-6 rounded-lg shadow-md border-l-4 border-orange-600 mb-8">
                <h3 class="text-2xl font-semibold text-orange-900 mb-3 flex items-center">
                    <span class="mr-2 text-3xl">🧭</span> 수업의 방향성
                </h3>
                <div class="grid md:grid-cols-3 gap-4 text-gray-800">
                    <div class="p-4 bg-white rounded-lg shadow-sm flex items-center">
                        <span class="text-orange-500 mr-2 text-2xl">🌍</span> 문화 교류
                    </div>
                    <div class="p-4 bg-white rounded-lg shadow-sm flex items-center">
                        <span class="text-orange-500 mr-2 text-2xl">🌳</span> 생태전환 교육
                    </div>
                    <div class="p-4 bg-white rounded-lg shadow-sm flex items-center">
                        <span class="text-orange-500 mr-2 text-2xl">🤖</span> AI 에듀테크
                    </div>
                </div>
                <p class="mt-4 text-gray-700 text-sm">
                    💡 이러한 방향성은 공통적으로 디지털/에듀테크 기반이며, 교육과정 재구성 또는 동아리 활동 기반으로 진행될 수 있습니다.
                </p>
            </div>

            <h3 class="text-3xl font-bold text-dark-blue mb-6 flex items-center">
                <span class="mr-2 text-yellow-600">📅</span> 연간 운영 계획 수립 (주제별)
            </h3>
            <div class="bg-white rounded-lg shadow-lg overflow-hidden mb-8">
                <table class="min-w-full divide-y divide-gray-200">
                    <thead class="bg-medium-teal">
                        <tr>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-teal-900 uppercase tracking-wider">주제</th>
                            <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-teal-900 uppercase tracking-wider">세부 내용</th>
                        </tr>
                    </thead>
                    <tbody class="bg-white divide-y divide-gray-200">
                        <tr class="hover-highlight">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                                <span class="text-teal-600 mr-2">😊</span> 자기소개 (Let me introduce myself)
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">
                                학생, 교사 자기소개, 학교 소개 등
                            </td>
                        </tr>
                        <tr class="hover-highlight">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                                <span class="text-teal-600 mr-2">🏫</span> 학교 소개 (School Music Video)
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">
                                학교 시설, 수업, 활동 등을 영상으로 소개
                            </td>
                        </tr>
                        <tr class="hover-highlight">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                                <span class="text-teal-600 mr-2">🗺️</span> 나라 소개 (Country)
                            </td>
                            <td class="px-6 py-4 text-sm text-gray-700">
                                국기, 대표 상징 소개, 카훗 퀴즈 게임 활용
                            </td>
                        </tr>
                        <tr class="hover-highlight">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                                <span class="text-teal-600 mr-2">🎁</span> 컬처박스 교환 (Culture box)
                            </td>
                            <td class="px-6 py-4 text-sm text-gray-700">
                                전통 놀이 용품, 전통 과자 키트, 우리나라 과자, 선물 교환. <br>
                                <span class="text-xs text-gray-600">
                                    *사전 협의 필수 (물품, 시기, 방법). 프로젝트 전 3~5월 또는 프로젝트 중 10~11월 활용. 국제우편(EMS)은 배송 2~3주 소요, 부피 기준 요금.
                                </span>
                            </td>
                        </tr>
                        <tr class="hover-highlight">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                                <span class="text-teal-600 mr-2">🎭</span> 전통 문화 체험
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">
                                전통 놀이, 음악, 전통 과자 만들기 등
                            </td>
                        </tr>
                        <tr class="hover-highlight">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                                <span class="text-teal-600 mr-2">🌱</span> 생태전환 교류
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">
                                물, 먹거리, 탄소중립, 자연환경, 기후변화/생태계 등
                            </td>
                        </tr>
                        <tr class="hover-highlight">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900">
                                <span class="text-teal-600 mr-2">🎄</span> 기타 (크리스마스 파티, 1:1 펜팔 등)
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-700">
                                기념일 파티, 편지 교환 등 자유로운 활동
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <section id="edutech" class="mb-16">
            <h2 class="text-4xl font-bold text-dark-blue mb-8 flex items-center">
                <span class="mr-3 text-purple-500">💻</span>3. 에듀테크 활용
            </h2>
            <p class="text-lg mb-8 text-gray-700 leading-relaxed">
                다양한 에듀테크 도구들을 활용하여 활동을 더욱 풍부하고 효율적으로 만들 수 있습니다.
            </p>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🎨</span> Canva
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        온라인 그래픽 디자인 플랫폼으로, 발표 자료나 포스터 제작에 용이하며 동시 협업이 가능합니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 자기소개 포스터</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 나라 상징 발표 자료</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 물 절약 실천 캠페인 포스터</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 학교 급식 소개 포스터 제작</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">📌</span> Padlet
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        온라인 협업 보드 플랫폼으로, 글, 사진, 영상 공유 게시판으로 활용됩니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 첫 만남 전 자기소개 자료 게시</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 나라 상징 포스터 제작 및 게시</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 물 절약 실천 캠페인 공유</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 친환경 손수건 제작</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 상대국 자연환경 탐구</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">📚</span> Book Creator
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        멀티미디어 전자책 제작 도구로, 이미지, 글, 오디오, 비디오 등을 넣어 디지털 책을 만들 수 있습니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> '물'을 주제로 동시 짓기</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 나라 상징 소개 책 만들기</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🎮</span> Kahoot
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        실시간 퀴즈 및 게임 플랫폼으로 학습 동기 유발과 흥미를 높이는 데 효과적입니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 나라 상징 학습 내용 정리</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 크리스마스 파티 게임</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🎲</span> Blooket
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        카훗과 유사한 실시간 퀴즈 및 게임 플랫폼입니다. 학생들의 참여와 학습 효율을 높일 수 있습니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 학습 내용 복습 퀴즈</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 팀별 경쟁 게임</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🎵</span> Suno AI
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        음악 이론이나 작곡 기술이 없어도 누구나 쉽게 자신만의 노래를 만들 수 있는 AI 작사/작곡 에듀테크입니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 다국어 환경 노래 제작 및 공유</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🎬</span> Vrew
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        AI 기술을 활용하여 영상을 쉽고 빠르게 편집하고 제작하는 프로그램입니다. 음성 인식 자동 자막 생성 및 텍스트로 AI 이미지/영상 만들기가 가능합니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 학교 소개 뮤직비디오 제작</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 모둠별 발표 영상 제작</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🎶</span> Musical Canvas
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        Google Arts & Culture에서 만든 도구로, 그림을 그리면 AI가 어울리는 음악을 만들어 줍니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 자기소개 시 좋아하는 보물을 AI 예술로 표현하고 음악 만들기</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🗣️</span> AI 번역기
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        텍스트, 음성 번역을 지원하며, 자기소개나 자료 제작 시 언어의 장벽을 낮추는 데 유용합니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 외국어 자기소개 준비</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 해외 자료 번역</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🖌️</span> AI 아트봉봉
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        AI 스케치 도안을 제작하는 데 활용됩니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 수업 관련 이미지 스케치 도안 제작</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🤸</span> Animated Drawings
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        학생들이 직접 그린 그림을 애니메이션으로 변환해주는 도구입니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 자기소개 활동 시 움직이는 캐릭터 표현</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">✍️</span> Autodraw
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        무료 웹 기반 AI 드로잉 도구로, 낙서처럼 그리면 AI가 유사한 그림을 제안하여 아이디어를 얻거나 표현의 폭을 넓힐 수 있습니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 해양 보호 생물 표현</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 생태 환경 로봇 그리기</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">💬</span> Wetoon
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        AI 웹툰 제작 플랫폼으로, AI 챗봇과 함께 줄거리를 쓰고 만화를 제작할 수 있습니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 환경 만화 제작</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">📊</span> Google 프레젠테이션
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        온라인에서 여러 명이 동시에 작업할 수 있는 프레젠테이션 도구입니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 나라 상징 발표 자료 협업 제작</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">🌎</span> Google Earth
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        세계 각지의 지리, 문화, 환경을 탐색할 수 있는 도구입니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 상대국 자연환경 탐구</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 우리 동네 자연환경 소개</li>
                        </ul>
                    </div>
                </div>

                <div class="bg-white p-6 rounded-lg shadow-md border-t-4 border-purple-500 flex flex-col">
                    <h3 class="text-2xl font-semibold text-purple-800 mb-3 flex items-center">
                        <span class="mr-2 text-3xl">👨‍💻</span> 코딩
                    </h3>
                    <p class="text-gray-700 mb-4 flex-grow">
                        학생들이 직접 코드를 작성하며 논리적 사고력과 문제 해결 능력을 기를 수 있습니다.
                    </p>
                    <div class="accordion-header cursor-pointer flex justify-between items-center text-purple-600 hover:text-purple-800 font-medium">
                        활용 예시 보기
                        <span class="accordion-icon transform transition-transform duration-300">▼</span>
                    </div>
                    <div class="accordion-content">
                        <ul class="list-none space-y-1 mt-3 text-sm text-gray-600">
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 간단한 게임 제작</li>
                            <li class="flex items-start"><span class="mr-1 text-purple-400">▪</span> 데이터 시각화 프로젝트</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <footer class="text-center text-gray-600 mt-12 py-8 border-t border-gray-200">
            <p>&copy; 2025 국제공동수업 기획 가이드. 모든 권리 보유.</p>
            <p class="mt-2">본 자료는 서울시교육청의 국제공동수업 확대 추진 정책을 기반으로 제작되었습니다.</p>
        </footer>
    </div>

    <script>
        document.querySelectorAll('.accordion-header').forEach(header => {
            header.addEventListener('click', () => {
                const content = header.nextElementSibling;
                const icon = header.querySelector('.accordion-icon');

                if (content.classList.contains('active')) {
                    content.classList.remove('active');
                    icon.style.transform = 'rotate(0deg)';
                } else {
                    content.classList.add('active');
                    icon.style.transform = 'rotate(180deg)';
                }
            });
        });
    </script>
</body>
</html>
