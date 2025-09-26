# Visiting-Windey
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>고급 레스토랑 메뉴 - 지그재그</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Gowun+Batang:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Gowun Batang', serif;
            background-color: #fdfaf5;
            color: #4a4a4a;
        }
        .menu-container {
            border: 2px solid #d3c5aa;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            position: relative; /* 이중 테두리를 위해 추가 */
        }
        /* 안쪽 테두리를 위한 스타일 추가 */
        .menu-container::before {
            content: '';
            position: absolute;
            top: 15px;
            left: 15px;
            right: 15px;
            bottom: 15px;
            border: 1px solid #e2d9c9;
            pointer-events: none;
        }
        .menu-title {
            color: #8c7851;
        }
        .menu-item-container {
            border-bottom: 1px solid #e2d9c9;
        }
        .menu-item-container:last-child {
            border-bottom: none;
        }
    </style>
</head>
<body class="bg-[#fdfaf5]">
    <div class="container mx-auto my-12 p-8 md:p-16 max-w-5xl bg-white menu-container">
        <!-- 레스토랑 이름과 메뉴 타이틀 -->
        <header class="text-center mb-16">
            <h1 class="text-5xl font-bold menu-title tracking-widest">Windey</h1>
            <p class="text-xl mt-3 text-gray-600 tracking-wider">정찬 메뉴</p>
        </header>

        <main class="space-y-12">
            <!-- 메뉴 리스트 -->
            <div class="space-y-10">
                <!-- 메뉴 아이템 1 -->
                <div class="md:flex items-center gap-8 menu-item-container pb-10">
                    <img src="https://i.postimg.cc/7fCjkDXF/1.jpg" alt="삼문어 간 사시미" class="w-full md:w-1/2 rounded-lg shadow-md mb-4 md:mb-0 object-cover h-64 md:h-80">
                    <div class="md:w-1/2">
                        <h3 class="text-3xl font-bold">삼문어 간 사시미</h3>
                        <p class="text-lg text-gray-500 mb-3">三文鱼拼鹅肝</p>
                        <p class="text-xl text-gray-700">신선한 연어 사시미와 부드러운 거위 간이 조화롭게 어우러진 요리입니다.</p>
                    </div>
                </div>

                <!-- 메뉴 아이템 2 -->
                <div class="md:flex items-center flex-row-reverse gap-8 menu-item-container pb-10">
                    <img src="https://i.postimg.cc/9rvKXSnc/2.jpg" alt="모단 육원" class="w-full md:w-1/2 rounded-lg shadow-md mb-4 md:mb-0 object-cover h-64 md:h-80">
                    <div class="md:w-1/2 md:text-right">
                        <h3 class="text-3xl font-bold">모단 육원</h3>
                        <p class="text-lg text-gray-500 mb-3">毛团肉圆</p>
                        <p class="text-xl text-gray-700">찹쌀로 겉을 덮어 쪄내어, 속은 촉촉하고 겉은 쫀득한 식감의 돼지고기 완자입니다.</p>
                    </div>
                </div>

                <!-- 메뉴 아이템 3 -->
                <div class="md:flex items-center gap-8 menu-item-container pb-10">
                    <img src="https://i.postimg.cc/QHRwNPy8/3.jpg" alt="문불 소고기" class="w-full md:w-1/2 rounded-lg shadow-md mb-4 md:mb-0 object-cover h-64 md:h-80">
                    <div class="md:w-1/2">
                        <h3 class="text-3xl font-bold">문불 소고기</h3>
                        <p class="text-lg text-gray-500 mb-3">文火小牛肉</p>
                        <p class="text-xl text-gray-700">오랜 시간 약한 불에서 정성껏 조리하여 입안에서 부드럽게 녹아내리는 소고기 요리입니다.</p>
                    </div>
                </div>
                
                <!-- 메뉴 아이템 4 -->
                <div class="md:flex items-center flex-row-reverse gap-8 menu-item-container pb-10">
                    <img src="https://i.postimg.cc/w7SZxPG6/5.jpg" alt="성게알과 어교를 곁들인 민물장어 조림" class="w-full md:w-1/2 rounded-lg shadow-md mb-4 md:mb-0 object-cover h-64 md:h-80">
                    <div class="md:w-1/2 md:text-right">
                        <h3 class="text-3xl font-bold">성게알과 어교를 곁들인 민물장어 조림</h3>
                        <p class="text-lg text-gray-500 mb-3">海胆花胶焖江鰻</p>
                        <p class="text-xl text-gray-700">고소한 성게알과 귀한 어교를 민물장어와 함께 조려낸 최고의 보양식입니다.</p>
                    </div>
                </div>
                
                <!-- 메뉴 아이템 5 -->
                <div class="md:flex items-center gap-8 menu-item-container pb-10">
                    <img src="https://i.postimg.cc/svtqf8ND/4.jpg" alt="건포 표고 버섯 자라찜" class="w-full md:w-1/2 rounded-lg shadow-md mb-4 md:mb-0 object-cover h-64 md:h-80">
                    <div class="md:w-1/2">
                        <h3 class="text-3xl font-bold">건포 표고 버섯 자라찜</h3>
                        <p class="text-lg text-gray-500 mb-3">干包蒸甲鱼</p>
                        <p class="text-xl text-gray-700">정성껏 말린 표고버섯의 깊은 향과 자라의 영양이 어우러진 귀한 찜 요리입니다.</p>
                    </div>
                </div>
                
                <!-- 메뉴 아이템 6 -->
                <div class="md:flex items-center flex-row-reverse gap-8 menu-item-container pb-10">
                    <img src="https://i.postimg.cc/yDc5DPMs/6.jpg" alt="송이버섯탕" class="w-full md:w-1/2 rounded-lg shadow-md mb-4 md:mb-0 object-cover h-64 md:h-80">
                    <div class="md:w-1/2 md:text-right">
                        <h3 class="text-3xl font-bold">송이버섯탕</h3>
                        <p class="text-lg text-gray-500 mb-3">松茸菌汤</p>
                        <p class="text-xl text-gray-700">자연 송이의 깊고 그윽한 향을 그대로 담아낸 맑고 개운한 탕입니다.</p>
                    </div>
                </div>
            </div>
        </main>

        <!-- 푸터 -->
        <footer class="text-center mt-16 pt-8 border-t-2 border-[#d3c5aa]">
            <p class="text-xl menu-title">Windey</p>
            <p class="text-gray-600 mt-2">한전 김동철 사장님을 포함한 모든 분들에게 최고의 맛과 정성을 선사합니다.</p>
        </footer>
    </div>
</body>
</html>

