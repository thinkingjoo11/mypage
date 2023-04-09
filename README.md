<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>

    <title>스파르타코딩클럽 | 부트스트랩 연습하기</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Gowun+Dodum&display=swap');

        * {
            font-family: 'Gowun Dodum', sans-serif;
        }

        .mytitle {
            background-color: green;
            color: white;

            height: 250px;

            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;

            background-image: linear-gradient(0deg, rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://movie-phinf.pstatic.net/20210715_95/1626338192428gTnJl_JPEG/movie_image.jpg');
            background-position: center;
            background-size: cover;
        }

        .mytitle>button {
            width: 250px;
            height: 50px;

            background-color: transparent;
            border: 1px solid white;
            color: white;

            border-radius: 50px;
            margin-top: 20px;
        }

        .mytitle>button:hover {
            border: 2px solid white;

        }

        .mycomnent {
            color: gray;
        }

        .mybtn {
               display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: center;

            margin-top: 20px;
        }

        .mybtn > button {
            margin-right: 10px;

            }
        

        .mycards {
            width: 1200px;
            margin: 20px auto 20px auto;
        }

        .mypost {
            /* background-color: green; */
            width:500px;
            margin: 20px auto 20px auto;
            padding: 20px 20px 20px 20px;
            box-shadow: 0px 0px 3px 0px gray;
        }
    </style>
</head>

<body>

    <div class="mytitle">
        <h1>내 생애 최고의 영화들</h1>
        <button>영화 기록하기</button>
    </div>
    <div class="mypost">


        <div class="form-floating mb-3">
            <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
            <label for="floatingInput">영화URL</label>
        </div>

        <div class="form-floating">
            <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
            <label for="floatingTextarea">코멘트</label>
        </div>
        <div class="mybtn">
            <button type="button" class="btn btn-dark">기록하기</button>
            <button type="button" class="btn btn-outline-dark">닫기</button>

        </div>
    </div>

    <div class="mycards">
        <div class="row row-cols-1 row-cols-md-4 g-4">

            <div class="col">
                <div class="card">
                    <img src="https://movie-phinf.pstatic.net/20210728_221/1627440327667GyoYj_JPEG/movie_image.jpg"
                        class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">영화제목이 들어갑니다</h5>
                        <p class="card-text">여기에 코멘트가 들어갑니다</p>
                        <p>⭐⭐⭐</p>
                        <p class="mycomment">여기에 나의 의견을 쓰면 되겠죠</p>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card">
                    <img src="https://movie-phinf.pstatic.net/20210728_221/1627440327667GyoYj_JPEG/movie_image.jpg"
                        class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">영화제목이 들어갑니다</h5>
                        <p class="card-text">여기에 코멘트가 들어갑니다</p>
                        <p>⭐⭐⭐</p>
                        <p class="mycomment">여기에 나의 의견을 쓰면 되겠죠</p>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card">
                    <img src="https://movie-phinf.pstatic.net/20210728_221/1627440327667GyoYj_JPEG/movie_image.jpg"
                        class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">영화제목이 들어갑니다</h5>
                        <p class="card-text">여기에 코멘트가 들어갑니다</p>
                        <p>⭐⭐⭐</p>
                        <p class="mycomment">여기에 나의 의견을 쓰면 되겠죠</p>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card">
                    <img src="https://movie-phinf.pstatic.net/20210728_221/1627440327667GyoYj_JPEG/movie_image.jpg"
                        class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">영화제목이 들어갑니다</h5>
                        <p class="card-text">여기에 코멘트가 들어갑니다</p>
                        <p>⭐⭐⭐</p>
                        <p class="mycomment">여기에 나의 의견을 쓰면 되겠죠</p>
                    </div>

                </div>
            </div>

        </div>



    </div>

</body>

</html>
