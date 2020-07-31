<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Portfolio</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700&display=swap" rel="stylesheet">
    <link href="https://cdn.rawgit.com/rastikerdar/vazir-font/v24.0.0/dist/font-face.css" rel="stylesheet"
          type="text/css"/>
    <style>
        div.paleBlueRows {
            border: 1px solid #FFFFFF;
            width: 95%;
            text-align: right;
            border-collapse: collapse;
            margin: 25px auto;
        }

        .divTable.paleBlueRows .divTableCell, .divTable.paleBlueRows .divTableHead {
            border: 1px solid #606362;
            padding: 6px 8px;
        }

        .divTable.paleBlueRows .divTableBody .divTableCell {
            font-size: 15px;
            direction: ltr;
            font-weight: 500;
            color: #c8cac8;
            position: relative;
        }

        .divTable.paleBlueRows .divTableBody .divTableRow:nth-child(even) {
            background: #050524;
        }

        .divTable.paleBlueRows .divTableBody .divTableRow:nth-child(odd) {
            background: #07061f;
        }

        .divTable.paleBlueRows .divTableHeading {
            background: #0B6FA4;
            background: -moz-linear-gradient(top, #4893bb 0%, #237dad 66%, #0B6FA4 100%);
            background: -webkit-linear-gradient(top, #4893bb 0%, #237dad 66%, #0B6FA4 100%);
            background: linear-gradient(to bottom, #4893bb 0%, #237dad 66%, #0B6FA4 100%);
            border-bottom: 5px solid brown;
        }

        .divTable.paleBlueRows .divTableHeading .divTableHead {
            font-size: 17px;
            font-weight: bold;
            color: #FFFFFF;
            text-align: center;
            border-left: 0px solid #FFFFFF;
        }

        .divTable.paleBlueRows .divTableHeading .divTableHead:first-child {
            border-left: none;
        }

        .paleBlueRows .tableFootStyle {
            font-size: 14px;
            font-weight: bold;
            color: #333333;
            background: #D0E4F5;
            border-top: 3px solid #444444;
        }

        .paleBlueRows .tableFootStyle {
            font-size: 16px;
            text-align: center;
        }

        /* DivTable.com */
        .divTable {
            display: table;
        }

        .divTableRow {
            display: table-row;
        }

        .divTableHeading {
            display: table-header-group;
        }

        .divTableCell, .divTableHead {
            display: table-cell;
        }

        .divTableHeading {
            display: table-header-group;
        }

        .divTableFoot {
            display: table-footer-group;
        }

        .divTableBody {
            display: table-row-group;
        }
    </style>
    <style>
        body {
            display: flex;
            flex-direction: column;
            direction: rtl;
            font-family: "Roboto", Vazir, serif;

        }

        @keyframes color-change {
            0% {
                background: #FFFF00;
            }
            100% {
                background: unset;
            }
        }

        .change {
            animation: color-change 3s ease-in;
        }

        .deactivated:before {
            content: '';
            width: 10px;
            height: 10px;
            background: #ff8a17;
            position: absolute;
            left: 5px;
            top: calc(50% - 5px);
            border-radius: 50px;
        }

    </style>
    <script
            src="https://code.jquery.com/jquery-3.5.1.min.js"
            integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0="
            crossorigin="anonymous"></script>
    <script type="text/javascript">
        var pixel_assets = {
            "IRO1BTEJ0001": [2320, 2124.81],
            "IRO3APOZ0001": [58, 65414.55],
            "IRO3DTDZ0001": [191, 57842.14],
            "IRO3YZTZ0001": [13, 40535.92],
            "IRO1PNES0001": [530, 21943.23],
            "IRO1SITA0001": [300, 15823.07],
            "IRO3RYHZ0001": [6, 25113.50],
            "IRO1NBAB0001": [48, 15558.40],
            "IRO1ZARM0001": [32, 39750],
        };
        var fari_assets = {
            "IRO1BTEJ0001": ["10900", "3028.97"],
            "IRO1KSIM0001": ["560", "60555.87"],
            "IRO3DTDZ0001": ["500", "56000.57"],
            "IRO1SORB0001": ["138", "157012.07"],
            "IRO1PNTB0001": ["380", "41935.23"],
            "IRO1KRTI0001": ["2490", "10738.87"],
            "IRO1BAFG0001": ["375", "43328.31"],
            "IRO1ROOI0001": ["250", "61371.44"],
            "IRO3DKHZ0001": ["200", "54435.49"],
            "IRO1GOLG0001": ["530", "20410.86"],
            "IRO1SADB0001": ["65", "80361.08"],
            "IRO1SITA0001": ["300", "15823.07"],
            "IRO1SEPP0001": ["200", "25402.31"],
            "IRO1SIMS0001": ["340", "16064.18"],
            "IRO1MNGZ0001": ["60", "85394.40"],
            "IRO3GAHZ0001": ["98", "53742.86"],
            "IRO1ZARM0001": ["32", "39897.44"],
            "IRO3GEDZ0001": ["50", "24087.16"],
            "IRO1NBAB0001": ["48", "15558.40"],
            "IRO1LPRS0001": ["74", "3214.80"],
            "IRO3RYHZ0001": ["6", "25113.50"]
        };
        var sajad_assets = {
            "IRO1SITA0001": ["300", "15823.07"],
            "IRO3DSNZ0001": ["200", "30163.31"],
            "IRO3GAHZ0001": ["120", "47992.88"],
            "IRO1ZARM0001": ["32", "39897.44"],
            "IRO1NBAB0001": ["48", "15558.40"],
            "IRO1LPRS0001": ["75", "3214.83"],
            "IRO3RYHZ0001": ["5", "25113.20"]
        };
        var zahra_assets = {
            "IRO1SITA0001": ["300", "15823.07"],
            "IRO1SIMS0001": ["300", "17109.01"],
            "IRO1ZARM0001": ["32", "39897.44"],
            "IRO1NBAB0001": ["48", "15558.40"],
            "IRO1LPRS0001": ["75", "3214.83"],
            "IRO3RYHZ0001": ["5", "25113.20"]
        };
        var setareh_assets = {
            "IRO1SITA0001": ["300", "15823.07"],
            "IRO1KSIM0001": ["70", "73338.71"],
            "IRO1ZARM0001": ["32", "39897.44"],
            "IRO1NBAB0001": ["48", "15558.40"],
            "IRO1LPRS0001": ["74", "3214.80"],
            "IRO3RYHZ0001": ["6", "25113.50"]
        };

        // var sajad = '["سيتا","300","15823.07","فاسمين","70","73338.71","غزر","32","39897.44","آبادا","48","15558.40","ولپارس","74","3214.80","رافزا","6","25113.50"]';
        // sajad = sajad.split("ك").join("ک");
        // sajad = sajad.split("ي").join("ی");

        // sajad = JSON.parse(sajad);
        // database = JSON.parse(database);
        // for (var i = 0; i < sajad.length; i += 3) {
        //     for (var j = 0; j < database.length; j++) {
        //         if (database[j]["sf"] === sajad[i]) {
        //             setareh_assets[database[j]["nc"]] = [sajad[i + 1], sajad[i + 2]];
        //         }
        //
        //     }
        // }
        // setareh_assets = JSON.stringify(setareh_assets);
        // console.log(setareh_assets)

    </script>
</head>
<body>

<div id="pixel" class="divTable paleBlueRows">
    <div class="divTableHeading">
        <div class="divTableRow">
            <div class="divTableHead">نماد</div>
            <div class="divTableHead">تعداد سهم</div>
            <div class="divTableHead">% تغییر</div>
            <div class="divTableHead">قیمت تمام شده</div>
            <div class="divTableHead">ارزش روز</div>
            <div class="divTableHead">سود و زیان</div>
            <div class="divTableHead">% سود</div>
        </div>
    </div>
    <div class="divTableBody">
        <!--        // Table Row - Cells-->
    </div>
    <div class="divTableFoot tableFootStyle">
        <div class="divTableRow">
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
        </div>
    </div>
</div>
<div id="fari" class="divTable paleBlueRows">
    <div class="divTableHeading">
        <div class="divTableRow">
            <div class="divTableHead">نماد</div>
            <div class="divTableHead">تعداد سهم</div>
            <div class="divTableHead">% تغییر</div>
            <div class="divTableHead">قیمت تمام شده</div>
            <div class="divTableHead">ارزش روز</div>
            <div class="divTableHead">سود و زیان</div>
            <div class="divTableHead">% سود</div>
        </div>
    </div>
    <div class="divTableBody">
        <!--        // Table Row - Cells-->
    </div>
    <div class="divTableFoot tableFootStyle">
        <div class="divTableRow">
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
        </div>
    </div>
</div>
<div id="sajad" class="divTable paleBlueRows">
    <div class="divTableHeading">
        <div class="divTableRow">
            <div class="divTableHead">نماد</div>
            <div class="divTableHead">تعداد سهم</div>
            <div class="divTableHead">% تغییر</div>
            <div class="divTableHead">قیمت تمام شده</div>
            <div class="divTableHead">ارزش روز</div>
            <div class="divTableHead">سود و زیان</div>
            <div class="divTableHead">% سود</div>
        </div>
    </div>
    <div class="divTableBody">
        <!--        // Table Row - Cells-->
    </div>
    <div class="divTableFoot tableFootStyle">
        <div class="divTableRow">
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
        </div>
    </div>
</div>
<div id="zahra" class="divTable paleBlueRows">
    <div class="divTableHeading">
        <div class="divTableRow">
            <div class="divTableHead">نماد</div>
            <div class="divTableHead">تعداد سهم</div>
            <div class="divTableHead">% تغییر</div>
            <div class="divTableHead">قیمت تمام شده</div>
            <div class="divTableHead">ارزش روز</div>
            <div class="divTableHead">سود و زیان</div>
            <div class="divTableHead">% سود</div>
        </div>
    </div>
    <div class="divTableBody">
        <!--        // Table Row - Cells-->
    </div>
    <div class="divTableFoot tableFootStyle">
        <div class="divTableRow">
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
        </div>
    </div>
</div>
<div id="setareh" class="divTable paleBlueRows">
    <div class="divTableHeading">
        <div class="divTableRow">
            <div class="divTableHead">نماد</div>
            <div class="divTableHead">تعداد سهم</div>
            <div class="divTableHead">% تغییر</div>
            <div class="divTableHead">قیمت تمام شده</div>
            <div class="divTableHead">ارزش روز</div>
            <div class="divTableHead">سود و زیان</div>
            <div class="divTableHead">% سود</div>
        </div>
    </div>
    <div class="divTableBody">
        <!--        // Table Row - Cells-->
    </div>
    <div class="divTableFoot tableFootStyle">
        <div class="divTableRow">
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell">0</div>
            <div class="divTableCell"></div>
        </div>
    </div>
</div>


<script type="application/javascript">
    var delay = 5000;

    function formatNumber(num) {
        return num.toString().replace(/(\d)(?=(\d{3})+(?!\d))/g, '$1,')
    }

    function fetch(assets, owner) {
        var url = "https://core.tadbirrlc.com//StockInformationHandler.ashx?%7B%22Type%22:%22getstockprice2%22,%22la%22:%22Fa%22,%22arr%22:%22";
        var endurl = "%22%7D&jsoncallback=";
        Object.keys(assets).forEach(function (entry) {
            url += entry + ",";
        });
        url += endurl;

        for (var i = 0; i < Object.keys(assets).length; i++) {
            $(`#${owner} .divTableBody`).append(`<div class="divTableRow"><div class="divTableCell">0</div><div class="divTableCell">0</div><div class="divTableCell">0</div><div class="divTableCell">0</div><div class="divTableCell">0</div><div class="divTableCell">0</div><div class="divTableCell">0</div></div>`);
        }


        // $('.divTable').on('DOMSubtreeModified', '.divTableCell', function () {
        //     var current = $(this);
        //     current.addClass("change");
        //     setTimeout(function () {
        //         current.removeClass("change");
        //     }, 3010);
        // });


        try {

            function myLoop() {
                setTimeout(function () {
                    $.get(url, function (datas, status) {
                        if (status === "success") {
                            console.log("d0ne!");
                            datas = datas.split("ك").join("ک");
                            datas = datas.split("ي").join("ی");
                            portfo = JSON.parse(datas);


                            //footer
                            var footer = $(`#${owner} .divTableFoot .divTableRow .divTableCell`);
                            footer.eq(0).html(owner);
                            var Ssahmcount = footer.eq(1);
                            var SgheymatTamamshode = footer.eq(3);
                            var SarzesheRooz = footer.eq(4);
                            var Sbenefit = footer.eq(5);

                            Ssahmcount.html(0);
                            SgheymatTamamshode.html(0);
                            SarzesheRooz.html(0);
                            Sbenefit.html(0);
                            Sbenefit.css("background", "linear-gradient(to bottom, #48F1E4 38%, #4FD7C5 65%, #0BFDF8 100%)");

                            $(`#${owner} .divTableBody .divTableRow`).each(function (index) {
                                if (Number(portfo[index].ss) === 1) {
                                    $(this).children().eq(0).removeClass("deactivated");
                                } else {
                                    $(this).children().eq(0).addClass("deactivated");
                                }


                                var symbol = portfo[index].sf;
                                var percent = portfo[index].lpvp;
                                var sahmcount = Number(assets[portfo[index].nc][0]);
                                var sahmprice = Number(assets[portfo[index].nc][1]);
                                var gheymatTamamShode = Math.round(sahmcount * sahmprice);
                                var arzesheRooz = Math.round(((sahmcount * portfo[index].ltp) - (sahmcount * portfo[index].ltp * 0.0088)));
                                var benefit = (arzesheRooz - gheymatTamamShode);
                                var benefitPercent = Math.round(benefit / gheymatTamamShode * 100);
                                var attrs = [symbol, sahmcount, (percent === 0) ? 0 : (percent + "  %  "), formatNumber(gheymatTamamShode), formatNumber(arzesheRooz), formatNumber(benefit), benefitPercent + "  %  "];
                                $(this).find('.divTableCell').each(function (index) {
                                    if (index === 2) {
                                        if (percent < 0) {
                                            $(this).css("color", "#d84c3c");
                                        } else if (percent > 0) {
                                            $(this).css("color", "#16a64d");
                                        }
                                    }
                                    if (index === 5) {
                                        if (benefit < 0) {
                                            $(this).css("color", "#d84c3c");
                                        } else if (benefit > 0) {
                                            $(this).css("color", "#16a64d");
                                        }
                                    }

                                    if ($(this).html() !== attrs[index]) {
                                        $(this).addClass("change");
                                        setTimeout(function () {
                                            $(this).removeClass("change");
                                        }, 3010);
                                    }
                                    $(this).html(attrs[index]);
                                });

                                Ssahmcount.html(Number(Ssahmcount.html()) + sahmcount);
                                SgheymatTamamshode.html(formatNumber(Number(SgheymatTamamshode.html().split(",").join("")) + gheymatTamamShode));
                                SarzesheRooz.html(formatNumber(Number(SarzesheRooz.html().split(",").join("")) + arzesheRooz));
                                Sbenefit.html(formatNumber(Number(Sbenefit.html().split(",").join("")) + benefit));

                            });
                        }
                    }).fail(function () {
                        console.log(fail)
                    });

                    myLoop();
                }, 5000)
            }

            myLoop();

        } catch (e) {
            console.log(e);
        }

    }

    var pixel_assets = {
        "IRO1BTEJ0001": [2320, 2124.81],
        "IRO3APOZ0001": [58, 65414.55],
        "IRO3DTDZ0001": [191, 57842.14],
        "IRO3YZTZ0001": [13, 40535.92],
        "IRO1PNES0001": [530, 21943.23],
        "IRO1SITA0001": [300, 15823.07],
        "IRO3RYHZ0001": [6, 25113.50],
        "IRO1NBAB0001": [48, 15558.40],
        "IRO1ZARM0001": [32, 39750],
    };


    fetch(pixel_assets, "pixel");
    fetch(fari_assets, "fari");
    fetch(sajad_assets, "sajad");
    fetch(zahra_assets, "zahra");
    fetch(setareh_assets, "setareh");

</script>
</body>
</html>
