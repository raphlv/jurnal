<div align="center">

# Academic Journal Portal - Research Paper Submission and Review

### *Peer Review Workflow, DOI Indexing, and PDF Manuscript Repository*

![PHP](https://img.shields.io/badge/PHP-8.2-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-10.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

---

</div>

## About The Project

Scientific research journal portal supporting blind peer-review workflows, editorial board assignment, issue volume publication, and open-access PDF downloads.

---

## Key Features

- Author Submission Portal: Upload manuscript PDFs, abstracts, keywords, and author affiliations.
- Double-Blind Peer Review: Reviewer assignment matrix with scoring criteria and revision feedback forms.
- Issue and Volume Publishing: Group accepted papers into periodic journal volumes with DOI metadata.
- Open-Access PDF Reader: In-browser PDF preview and download metrics tracking.

---

## Technology Stack

- Backend: Laravel 10 (PHP 8.2)
- Database: MySQL 8.0
- Storage: Public PDF Manuscript Storage Driver

---

## Getting Started

`ash
git clone https://github.com/raphlv/jurnal.git
cd jurnal
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
`

---

## Developer and Maintainer
Pangeran Ryan Pahlevi - https://pangeranryan.vercel.app

<!-- Last updated: 2026-09-01 14:35:44 -->
