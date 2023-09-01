---
toc: false
comments: false
hide: true
layout: post
title: JS Output Personal
courses: { compsci: {week: 2} }
type: hacks
---

### Markdown Table
Monday, Tuesday, Thursday Schedule

| Class Period | Course Title | Time        |
| -----------  | -----------  | ----------- |
| 1            | AP Gov       | 8:35 - 9:44 |
| 2            | AP CSP       | 9:49 - 10:58 |
| Break        | Break        | 10:58 - 11:08 |
| 3            | Library      | 11:13 - 12:22 |
| Lunch        | Lunch        | 12:22 - 12:52 |
| 4            | AP Stats     | 12:57 - 2:06 |
| OH           | Office Hours | 2:06 - 2:31 |
| 5            | Offroll      | 2:36 - 3:45 |


### HTML Table

Wednesday (Late Start) Schedule

<table class="table">
    <thead>
        <tr>
            <th>Class Period</th>
            <th>Course Title</th>
            <th>Time</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>AP Gov</td>
            <td>9:55 - 10:53</td>
        </tr>
        <tr>
            <td>2</td>
            <td>AP CSP</td>
            <td>10:58 - 11:56</td>
        </tr>
        <tr>
            <td>Break</td>
            <td>Break</td>
            <td>11:56 - 12:06</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Library</td>
            <td>12:11 - 1:09</td>
        </tr>
        <tr>
            <td>Lunch</td>
            <td>Lunch</td>
            <td>1:09 - 1:39</td>
        </tr>
        <tr>
            <td>4</td>
            <td>AP Stats</td>
            <td>1:44 - 2:42</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Offroll</td>
            <td>2:47 - 3:45</td>
        </tr>
    </tbody>
</table>

### HTML Table with JavaScript jquery

Friday Schedule

<!-- Head contains information to Support the Document -->
<head>
    <!-- load jQuery and DataTables output style and scripts -->
    <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.13.4/css/jquery.dataTables.min.css">
    <script type="text/javascript" language="javascript" src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>var define = null;</script>
    <script type="text/javascript" language="javascript" src="https://cdn.datatables.net/1.13.4/js/jquery.dataTables.min.js"></script>
</head>

<!-- Body contains the contents of the Document -->
<body>
    <table id="demo" class="table">
        <thead>
        <tr>
            <th>Class Period</th>
            <th>Course Title</th>
            <th>Time</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>AP Gov</td>
            <td>8:35 - 9:49</td>
        </tr>
        <tr>
            <td>2</td>
            <td>AP CSP</td>
            <td>9:54 - 11:08</td>
        </tr>
        <tr>
            <td>Break</td>
            <td>Break</td>
            <td>11:08 - 11:18</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Library</td>
            <td>11:23 - 12:37</td>
        </tr>
        <tr>
            <td>Lunch</td>
            <td>Lunch</td>
            <td>12:37 - 1:07</td>
        </tr>
        <tr>
            <td>4</td>
            <td>AP Stats</td>
            <td>1:12 - 2:26</td>
        </tr>
        <tr>
            <td>5</td>
            <td>Offroll</td>
            <td>2:31 - 3:45</td>
        </tr>
        </tbody>
    </table>
</body>

<!-- Script is used to embed executable code -->
<script>
    $("#demo").DataTable();
</script>
