# Link Integrity Audit Report

This report presents the findings of a comprehensive link integrity audit conducted on the workspace files.

## Executive Summary

| Metric | Count |
| :--- | :--- |
| **Total Files Scanned** | 1 |
| **Total Unique Links Extracted** | 16 |
| **Total Working Links (HTTP 200)** | 14 |
| **Total Broken Links (HTTP 404/Error)** | 2 |

> [!NOTE]  
> The 2 links flagged as returning HTTP 404 are Google Fonts preconnect links (`<link rel="preconnect" ...>`). These are connection initialization endpoints and do not serve standard HTML pages on direct HTTP GET requests, which explains the 404 status. They are not actually broken in the context of the application.

---

## Workspace Files Scanned

- [soft_computing_makaut_youtube_master_playlist.html](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html)

---

## Broken / Flagged Links

Below is the list of links that did not return an HTTP 200 status code:

### 1. `https://fonts.googleapis.com`
- **HTTP Status Code:** `404`
- **Error Details:** `HTTP Error 404: Not Found`
- **File & Line Occurrences:**
  - [soft_computing_makaut_youtube_master_playlist.html:L13](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L13)
- **Context:** Used as a preconnect element to speed up Google Fonts stylesheet fetching. This is expected behavior for connection prefetching.

### 2. `https://fonts.gstatic.com`
- **HTTP Status Code:** `404`
- **Error Details:** `HTTP Error 404: Not Found`
- **File & Line Occurrences:**
  - [soft_computing_makaut_youtube_master_playlist.html:L14](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L14)
- **Context:** Used as a preconnect element with `crossorigin` to optimize Google Fonts asset delivery. This is expected behavior for connection prefetching.

---

## Working Links (HTTP 200)

The following links resolved successfully:

| Link | Total Occurrences | File & Key Lines |
| :--- | :---: | :--- |
| `https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Outfit:wght@700;800&display=swap` | 1 | [L15](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L15) |
| `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css` | 1 | [L18](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L18) |
| `https://www.youtube.com/watch?v=L26Y92_1Pds` | 5 | [L899](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L899), [L962](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L962), [L1088](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1088), [L1823](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1823), [L4152](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L4152) |
| `https://www.youtube.com/watch?v=kYJq068r38s` | 51 | [L920](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L920), [L1067](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1067), [L1151](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1151) ... |
| `https://www.youtube.com/watch?v=kxhH1RsR4CE` | 1 | [L941](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L941) |
| `https://www.youtube.com/watch?v=h2d_nJ4l53A` | 4 | [L983](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L983), [L1193](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1193), [L1214](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1214), [L2222](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L2222) |
| `https://www.youtube.com/watch?v=dg5zUxdAE_E` | 15 | [L1004](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1004), [L1025](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1025), [L1046](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1046) ... |
| `https://www.youtube.com/watch?v=H9PAc_8n68A` | 18 | [L1277](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1277), [L1298](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1298), [L1319](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1319) ... |
| `https://www.youtube.com/watch?v=F05E1k6s-3k` | 74 | [L1487](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1487), [L1508](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1508), [L1529](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1529) ... |
| `https://www.youtube.com/watch?v=FwPgHgbncPk` | 32 | [L1655](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1655), [L1676](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L1676), [L3293](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L3293) ... |
| `https://www.youtube.com/watch?v=al0HRxB8bc0` | 7 | [L2537](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L2537), [L3797](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L3797), [L3818](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L3818) ... |
| `https://youtu.be/QZ8ieXZVjuE` | 4 | [L3041](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L3041), [L3899](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L3899), [L3905](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L3905), [L4384](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L4384) |
| `https://www.youtube.com/watch?v=kYJ5oVbVp80` | 2 | [L3713](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L3713), [L4512](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L4512) |
| `https://www.youtube-nocookie.com/embed/$` | 1 | [L4624](file:///e:/CODING/Sem-%206/Soft%20Computing/soft_computing_makaut_youtube_master_playlist.html#L4624) (Part of JS template literal code) |

---

## Methodology
1. **Extraction**: A Python script was run to scan the workspace directory recursively for `html`, `js`, `css`, and `md` files, extracting all absolute URL sequences using regular expressions.
2. **De-duplication**: Identified 16 unique URLs from the workspace.
3. **HTTP Requests**: Sent automated HTTP GET requests using a realistic browser `User-Agent` (`Mozilla/5.0 ... Chrome/120.0.0.0 Safari/537.36`) to record HTTP status codes. SSL verification was disabled to prevent local environment configuration issues from skewing the results.
