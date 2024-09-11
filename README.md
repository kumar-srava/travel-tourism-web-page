# travel-tourism-web-page
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="style.css">
</head>


<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
    <div id="sectionHome">
        <div class="bg-container d-flex flex-column justify-content-end">
            <div class="tourism-card">
                <h1 class="main-heading">Tourism</h1>
                <p class="paragraph">Plan your trip.</p>
                <button class="button" onclick="display('sectionFavouritePlaces')">Get Started</button>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div id="sectionFavouritePlaces">
                    <div class="favourite-places-bg-container">
                        <h1 class="favourite-places-heading">Favourite Places</h1>
                        <div class="container">
                            <div class="row">
                                <div class="col-12">
                                    <div class="favourite-place-card-container m-5 p-3 d-flex flex-row" onclick="display('sectionTajMahalDetailedView')">
                                        <div>
                                            <h1 class="favourite-place-card-heading">Taj Mahal</h1>
                                            <p class="favourite-place-card-description">
                                                If there was just one symbol to represent all of India, it would be the
                                                Taj Mahal.It was located in Agra at near by New Delhi capital of india.
                                            </p>
                                        </div>
                                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png" class="favourite-place-card-image ml-5" />
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="container">
                            <div class="row">
                                <div class="col-12">
                                    <div class="favourite-place-card-container m-5 p-3 d-flex flex-row" onclick="display('sectionGoldenTempleDetailedView')">
                                        <div>
                                            <h1 class="favourite-place-card-heading">Golden Temple</h1>
                                            <p class="favourite-place-card-description">
                                                Amritsar is world-famous for the beautiful and highly revered Golden
                                                Temple.It is named after sikh warrior and ramgarhia misl chief Jasa singh ramgarhia.
                                            </p>
                                        </div>
                                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png" class="favourite-place-card-image  ml-5" />
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="container">
                            <div class="row">
                                <div class="col-12">
                                    <div class="favourite-place-card-container m-5 p-3 d-flex flex-row" onclick="display('sectionmysorepalacedetailedview')">
                                        <div>
                                            <h1 class="favourite-place-card-heading">Mysore Palace</h1>
                                            <p class="favourite-place-card-description">
                                                The Mysore Palace is a historical palace and the royal residence at
                                                Mysore .This historical architecture is located in Mysore in Karnataka 
                                                state.
                                            </p>
                                        </div>
                                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png" class="favourite-place-card-image ml-5" />
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="container">
                            <div class="row">
                                <div class="col-12">
                                    <div class="favourite-place-card-container m-5 p-3 d-flex flex-row" onclick="display('sectionvaranasitemple')">
                                        <div>
                                            <h1 class="favourite-place-card-heading">Varanasi Temple</h1>
                                            <p class="favourite-place-card-description">
                                                Varanasi Temple is most famous Hindu temples dedicated to Lord Shiva.and it is located in 
                                                varanasi called as kaasi one of the famous temple of lord shiva.
                                            </p>
                                        </div>
                                        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png" class="favourite-place-card-image ml-5" />
                                    </div>
                                </div>
                            </div>
                        </div>
                        <button class="btn btn-dark" onclick="display('sectionHome')">back</button>
                    </div>
                </div>
            </div>
        </div>
    </div></div></div></div>
    <div id="sectionTajMahalDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="carouselExampleIndicators1" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#carouselExampleIndicators1" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#carouselExampleIndicators1" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Taj Mahal</h1>
                    <p class="detailed-view-card-description">
                        The Taj Mahal is considered to be the greatest architectural achievement
                        in the whole range of Indo-Islamic architecture. Its recognised
                        architectonic beauty has a rhythmic combination of solids and voids,
                        concave and convex and light shadow; such as arches and domes further
                        increases the aesthetic aspect. Not a piece of architecture, as other
                        buildings are, but the proud passions of an emperor’s love wrought in
                        living stones.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>
    <div id="sectionGoldenTempleDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Golden Temple</h1>
                    <p class="detailed-view-card-description">
                        The Golden Temple, also known as Harmandir Sahib is a gurdwara
                        located in the city of Amritsar, Punjab, India. There are many
                        places to visit Near Golden Temple.
                    </p>
                    <ol class="detailed-view-card-description">
                        <li>Jallianwala Bagh</li>
                        <li>Wagah Border</li>
                        <li>Harike Wetland</li>
                        <li>Bathinda Fort</li>
                    </ol>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>
    <div id="sectionmysorepalacedetailedview">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Mysore Palace</h1>
                    <p class="detailed-view-card-description">
                        Mysore Palace is also called as Ambar Vilas Palace, is one of the most magnificient and largest palace
                        in india. Situated in the southern state karnataka. It used to be then official residence of the Wodeyar
                        Dynasty, the rules of mysore from 1399 to 1950. The grand palace stands tall in the heart of Mysore city.


                    </p>
                    <ol class="detailed-view-card-description">
                        <li>Sommathpur Temple</li>
                        <li>Devaraj Market</li>
                        <li>Melkote</li>

                    </ol>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>
    <div id="sectionvaranasitemple">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Varanasi Temple</h1>
                    <p class="detailed-view-card-description">
                        Sri Kashi Vishwanth Temple Temple also know as the Golden Temple, it is dedicated to lord shiva, the presiding
                        deity of the city. Varanasi is said to be the point at which the first jyotirlinga, the fiery pillar of light by
                        which shiva manifested has supermercy over others gods, broke through the earths crust and flared towards the heavens. More
                        than the Gaths and even the Ganga, the shivalinga installed in the temple remains the devotional focus of Varanasi.
                    </p>
                    <ol class="detailed-view-card-description">
                        <li>Dashwamedh Ghat</li>
                        <li>Manikarnika</li>
                        <li>Assi Gaht </li>
                        <li>Sarnath Museam</li>
                    </ol>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>


    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>
