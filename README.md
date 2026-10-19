<a id="readme-top"></a>

<br />
<div align="center">
  <h3 align="center">SQLite Database Design</h3>
  <p align="center">
    Relational database design, normalization, and data integrity exercises with Python and SQLite - CIS 3120 coursework at Baruch College
    <br />
    <a href="https://github.com/Swikc4/sqlite-database-design"><strong>Explore the repo »</strong></a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul><li><a href="#built-with">Built With</a></li></ul>
    </li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#what-i-practiced">What I Practiced</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

Coursework from CIS 3120 Programming for Analytics at Baruch College, focused on relational database design and data integrity using Python and SQLite.

The notebook works through six sections:

1. Environment setup
2. Foreign key mechanics - enforcement, `rowid` and `AUTOINCREMENT`, valid and invalid inserts, and what happens when you delete a parent row
3. Normalization - spotting the problem in a flat table and decomposing it into a normalized schema
4. Multi-table querying - joins across a library database, members who never borrowed, outstanding loans, and total fines per member
5. Data integrity scenarios - correct deletion order and `PRAGMA foreign_keys` OFF vs ON
6. Schema design challenge - designing, implementing, populating, and querying a new schema

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
* ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
* ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

### Prerequisites

* Python 3 (SQLite support is built in through the `sqlite3` standard library)
* Jupyter Notebook or Google Colab
  ```sh
  pip install notebook
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Swikc4/sqlite-database-design.git
   ```
2. Open `Module10_ForeignKeys_Normalization.ipynb` in Jupyter or upload it to Colab.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

Run the notebook cells from top to bottom. Each section creates small in-memory or file-based SQLite databases, so there is nothing to install or configure. The full notebook runs start to finish without errors and each exercise prints its query results inline.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## What I Practiced

Through this work, I practiced creating relational schemas, defining relationships between tables, enforcing data integrity with foreign keys, identifying normalization issues, and querying data across multiple related tables.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

* CIS 3120 Programming for Analytics, Baruch College (Zicklin School of Business)
