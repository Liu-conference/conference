<!-- <!DOCTYPE html> -->
<!-- <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conference Schedule</title> -->
<style>
    /* 全局样式重置 + 基础设置 */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: "Newsreader", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji", serif;
    }
    body {
        padding: 20px;
    }
    .schedule-table {
        border-collapse: collapse;
        width: 100%;
        font-size: 18px;
        table-layout: fixed; /* 固定列宽，避免内容撑开变形 */
        min-width: 600px;
    }
    /* 表头单元格样式 */
    .schedule-table th {
        background-color: #8da9d4; /* 浅蓝底色 */
        color: white;
        font-weight: bold;
        padding: 12px 8px;
        border: 2px solid black;
        text-align: center;
    }
    /* 内容单元格样式 */
    .schedule-table td {
        padding: 10px 8px;
        border: 2px solid black;
        vertical-align: middle;
    }
    /* 日期列样式（左侧固定列） */
    .date-cell {
        background-color: #8da9d4;
        color: white;
        font-weight: bold;
        text-align: center;
        vertical-align: middle;
    }
    .break-row td {
        background-color: #e9e9e9; /* 浅灰底色 */
        text-align: center;
        font-weight: bold;
        height: 80%;
    }
    .title-cell {
        text-align: left;
    }
    .speaker-cell {
        text-align: center;
    }
    .time-cell {
        text-align: center;
    }
</style>
<!-- </head> -->

<div>
    <table class="schedule-table">
        <colgroup>
        <col style="width: 10%; min-width:200px;">    <!-- Date 日期列 -->
        <col style="width: 12%;">   <!-- Time 时间列 -->
        <col style="width: 65%;">   <!-- Title 标题列 -->
        <col style="width: 15%;">   <!-- Speaker 发言人列 -->
        </colgroup>
        <thead>
            <tr>
                <th>Date</th>
                <th>Time</th>
                <th>Title</th>
                <th>Speaker</th>
            </tr>
        </thead>
        <tbody>
            <!-- 第一行-->
            <tr>
                <td rowspan="7" class="date-cell">July 1<br>Wed.</td>
                <td class="time-cell">9:30-10:30</td>
                <td class="title-cell">Isomonodromic Deformations of Higgs Bundles and a Characterization of the Non-Abelian Noether–Lefschetz Locus</td>
                <td class="speaker-cell">Kang Zuo</td>
            </tr>
            <!-- 第二行 -->
            <tr class="break-row">
                <td>10:30-11:00</td>
                <td colspan="2">Group Photo and Break</td>
            </tr>
            <!-- 第三行 -->
            <tr>
                <td class="time-cell">11:00-12:00</td>
                <td class="title-cell">An update on archimedean, birational, and motivic zeta functions</td>
                <td class="speaker-cell">Nero Budur</td>
            </tr>
            <!-- 第四行 -->
            <tr class="break-row">
                <td></td>
                <td colspan="2">Lunch</td>
            </tr>
            <!-- 第五行 -->
            <tr>
                <td class="time-cell">14:00-15:00</td>
                <td class="title-cell">Filtrations and Bloch's conjecture for zero cycles of hyperkähler varieties of known types</td>
                <td class="speaker-cell">Zhiyuan Li</td>
            </tr>
            <!-- 第六行 -->
            <tr class="break-row">
                <td>15:00-15:30</td>
                <td colspan="2">Break</td>
            </tr>
            <!-- 第七行 -->
            <tr>
                <td class="time-cell">15:30-16:30</td>
                <td class="title-cell">On irregular 3 folds of general type with small canonical volumes</td>
                <td class="speaker-cell">Zhi Jiang</td>
            </tr>
        </tbody>
    </table>
    <br>
    <table class="schedule-table">
        <colgroup>
        <col style="width: 10%; min-width:200px;">    <!-- Date -->
        <col style="width: 12%;">   <!-- Time -->
        <col style="width: 65%;">   <!-- Title -->
        <col style="width: 15%;">   <!-- Speaker -->
        </colgroup>
        <thead>
            <tr>
                <th>Date</th>
                <th>Time</th>
                <th>Title</th>
                <th>Speaker</th>
            </tr>
        </thead>
        <tbody>
            <!-- 第一行 -->
            <tr>
                <td rowspan="7" class="date-cell">July 2<br>Thu.</td> 
                <td class="time-cell">9:30-10:30</td>
                <td class="title-cell">A conjectural characteristic-class version of the Hodge index theorem for singular complex algebraic varieties
                </td>
                <td class="speaker-cell">Laurentiu Maxim
                </td>
            </tr>
            <!-- 第二行 -->
            <tr class="break-row">
                <td>10:30-11:00</td>
                <td colspan="2">Break</td> 
            </tr>
            <!-- 第三行 -->
            <tr>
                <td class="time-cell">11:00-12:00</td>
                <td class="title-cell">Automorphism Groups of Cubic Fourfolds: An Overview and New Results
                </td>
                <td class="speaker-cell">Zhiwei Zheng
                </td>
            </tr>
            <!-- 第四行 -->
            <tr class="break-row">
                <td></td>
                <td colspan="2">Lunch</td>
            </tr>
            <!-- 第五行 -->
            <tr>
                <td class="time-cell">14:00-15:00</td>
                <td class="title-cell">Abelian automorphism groups of surfaces of general type
                </td>
                <td class="speaker-cell">Xin Lv
                </td>
            </tr>
            <!-- 第六行 -->
            <tr class="break-row">
                <td>15:00-15:30</td>
                <td colspan="2">Break</td>
            </tr>
            <!-- 第七行 -->
            <tr>
                <td class="time-cell">15:30-16:30</td>
                <td class="title-cell">On the image of a certain Prym map
                </td>
                <td class="speaker-cell">Zheng Zhang
                </td>
            </tr>
        </tbody>
    </table>
    <br>
    <table class="schedule-table">
        <colgroup>
        <col style="width: 10%; min-width:200px;">    <!-- Date -->
        <col style="width: 12%;">   <!-- Time -->
        <col style="width: 65%;">   <!-- Title -->
        <col style="width: 15%;">   <!-- Speaker -->
        </colgroup>
        <thead>
            <tr>
                <th>Date</th>
                <th>Time</th>
                <th>Title</th>
                <th>Speaker</th>
            </tr>
        </thead>
        <tbody>
            <!-- 第一行 -->
            <tr>
                <td rowspan="7" class="date-cell">July 3<br>Fri.</td> 
                <td class="time-cell">9:30-10:30</td>
                <td class="title-cell">Irrational pencils, varieties isogenous to a product and the action of the absolute Galois group GAL on the connected components of moduli spaces
                </td>
                <td class="speaker-cell">Fabrizio Catanese
                </td>
            </tr>
            <!-- 第二行 -->
            <tr class="break-row">
                <td>10:30-11:00</td>
                <td colspan="2">Break</td> 
            </tr>
            <!-- 第三行 -->
            <tr>
                <td class="time-cell">11:00-12:00</td>
                <td class="title-cell">Rigidity problems and finiteness results on moduli spaces of polarized manifolds
                </td>
                <td class="speaker-cell">Ruiran Sun
                </td>
            </tr>
            <!-- 第四行 -->
            <tr class="break-row">
                <td></td>
                <td colspan="2">Lunch</td>
            </tr>
            <tr class="break-row">
                <td></td>
                <td colspan="2">Free afternoon</td>
            </tr>
        </tbody>
    </table>
    <br>
    <table class="schedule-table">
        <colgroup>
        <col style="width: 10%; min-width:200px;">    <!-- Date -->
        <col style="width: 12%;">   <!-- Time -->
        <col style="width: 65%;">   <!-- Title -->
        <col style="width: 15%;">   <!-- Speaker -->
        </colgroup>
        <thead>
            <tr>
                <th>Date</th>
                <th>Time</th>
                <th>Title</th>
                <th>Speaker</th>
            </tr>
        </thead>
        <tbody>
            <!-- 第一行 -->
            <tr>
                <td rowspan="7" class="date-cell">July 4<br>Sat.</td> 
                <td class="time-cell">9:30-10:30</td>
                <td class="title-cell">A Riemann-Hilbert correspondence in positive characteristic and its applications
                </td>
                <td class="speaker-cell">Adrian Langer
                </td>
            </tr>
            <!-- 第二行 -->
            <tr class="break-row">
                <td>10:30-11:00</td>
                <td colspan="2">Break</td> 
            </tr>
            <!-- 第三行 -->
            <tr>
                <td class="time-cell">11:00-12:00</td>
                <td class="title-cell">The geometry of Hessenberg and Lusztig varieties
                </td>
                <td class="speaker-cell">Patrick Brosnan
                </td>
            </tr>
            <!-- 第四行 -->
            <tr class="break-row">
                <td></td>
                <td colspan="2">Lunch</td>
            </tr>
            <!-- 第五行 -->
            <tr>
                <td class="time-cell">14:00-15:00</td>
                <td class="title-cell">Dicritical divisors and hypercurvettes
                </td>
                <td class="speaker-cell">Wim Veys
                </td>
            </tr>
            <!-- 第六行 -->
            <tr class="break-row">
                <td>15:00-15:30</td>
                <td colspan="2">Break</td>
            </tr>
            <!-- 第七行 -->
            <tr>
                <td class="time-cell">15:30-16:30</td>
                <td class="title-cell">Hodge theory for secant varieties
                </td>
                <td class="speaker-cell">Qianyu Chen
                </td>
            </tr>
        </tbody>
    </table>
    <br>
    <table class="schedule-table">
        <colgroup>
        <col style="width: 10%; min-width:200px;">    <!-- Date -->
        <col style="width: 12%;">   <!-- Time -->
        <col style="width: 65%;">   <!-- Title -->
        <col style="width: 15%;">   <!-- Speaker -->
        </colgroup>
        <thead>
            <tr>
                <th>Date</th>
                <th>Time</th>
                <th>Title</th>
                <th>Speaker</th>
            </tr>
        </thead>
        <tbody>
            <!-- 第一行 -->
            <tr>
                <td rowspan="7" class="date-cell">July 5<br>Sun.</td> 
                <td class="time-cell">9:30-10:30</td>
                <td class="title-cell">Equivariant motivic Integration for formal schemes and applications to singularities
                </td>
                <td class="speaker-cell">Quy Thuong Le
                </td>
            </tr>
            <!-- 第二行 -->
            <tr class="break-row">
                <td>10:30-11:00</td>
                <td colspan="2">Break</td> 
            </tr>
            <!-- 第三行 -->
            <tr>
                <td class="time-cell">11:00-12:00</td>
                <td class="title-cell">Finiteness of Crystalline Representations
                </td>
                <td class="speaker-cell">Jinbang Yang
                </td>
            </tr>
            <!-- 第四行 -->
            <tr class="break-row">
                <td></td>
                <td colspan="2">Lunch</td>
            </tr>
            <tr class="break-row">
                <td></td>
                <td colspan="2">Free afternoon</td>
            </tr>
        </tbody>
    </table>
</div>

<!-- <div>
    <table class="schedule-table">
        <colgroup>
        <col style="width: 10%; min-width:200px;">
        <col style="width: 12%;">
        <col style="width: 65%;">
        <col style="width: 15%;">
        </colgroup>
        <thead>
            <tr>
                <th>Date</th>
                <th>Time</th>
                <th>Title</th>
                <th>Speaker</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td rowspan="7" class="date-cell">July 1<br>Wed.</td> 
                <td class="time-cell">9:30-10:30</td>
                <td class="title-cell">
                </td>
                <td class="speaker-cell">
                </td>
            </tr>

            <tr class="break-row">
                <td>10:30-11:00</td>
                <td colspan="2">Break</td> 
            </tr>

            <tr>
                <td class="time-cell">11:00-12:00</td>
                <td class="title-cell">
                </td>
                <td class="speaker-cell">
                </td>
            </tr>

            <tr class="break-row">
                <td></td>
                <td colspan="2">Lunch</td>
            </tr>

            <tr>
                <td class="time-cell">14:00-15:00</td>
                <td class="title-cell">
                </td>
                <td class="speaker-cell">
                </td>
            </tr>

            <tr class="break-row">
                <td>15:00-15:30</td>
                <td colspan="2">Break</td>
            </tr>

            <tr>
                <td class="time-cell"></td>
                <td class="title-cell">
                </td>
                <td class="speaker-cell">
                </td>
            </tr>
        </tbody>
    </table>
</div> -->

