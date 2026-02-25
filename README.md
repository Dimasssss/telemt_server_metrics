# Server Metrics 2026-02-25 23:23:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 1548.4 (0h 25m)
telemt_connections_total 13320
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 363
telemt_me_keepalive_sent_total 1595
telemt_me_keepalive_pong_total 1595
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 87
telemt_me_route_drop_no_conn_total 1481
telemt_desync_total 12
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_pool_force_close_total 12
telemt_pool_stale_pick_total 294
telemt_me_writer_removed_total 97
telemt_me_writer_removed_unexpected_total 69
telemt_me_refill_triggered_total 59
telemt_me_refill_skipped_inflight_total 10
telemt_me_writer_restored_same_endpoint_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 12340
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 37512108 (35.77 MB)
telemt_user_octets_to_client{user="hello"} 2595710704 (2.42 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 2342.7 (0h 39m)
telemt_connections_total 8811
telemt_connections_bad_total 412
telemt_handshake_timeouts_total 364
telemt_me_keepalive_sent_total 2544
telemt_me_keepalive_pong_total 2544
telemt_me_reconnect_attempts_total 114
telemt_me_reconnect_success_total 142
telemt_me_route_drop_no_conn_total 1439
telemt_desync_total 11
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 2
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 367
telemt_me_writer_removed_total 175
telemt_me_writer_removed_unexpected_total 119
telemt_me_refill_triggered_total 109
telemt_me_refill_skipped_inflight_total 10
telemt_me_writer_restored_same_endpoint_total 107
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 7918
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 26390884 (25.17 MB)
telemt_user_octets_to_client{user="hello"} 1396982288 (1.30 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 10070.1 (2h 47m)
telemt_connections_total 66173
telemt_connections_bad_total 1339
telemt_handshake_timeouts_total 15804
telemt_me_keepalive_sent_total 10995
telemt_me_keepalive_pong_total 10990
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 584
telemt_me_reconnect_success_total 638
telemt_me_route_drop_no_conn_total 12319
telemt_desync_total 161
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 10
telemt_pool_force_close_total 116
telemt_pool_stale_pick_total 1734
telemt_me_writer_removed_total 882
telemt_me_writer_removed_unexpected_total 599
telemt_me_refill_triggered_total 573
telemt_me_refill_skipped_inflight_total 26
telemt_me_writer_restored_same_endpoint_total 570
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 47332
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 393236372 (375.02 MB)
telemt_user_octets_to_client{user="hello"} 13259514064 (12.35 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 12475.8 (3h 27m)
telemt_connections_total 79786
telemt_connections_bad_total 229
telemt_handshake_timeouts_total 8228
telemt_me_keepalive_sent_total 13916
telemt_me_keepalive_pong_total 13905
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 707
telemt_me_reconnect_success_total 767
telemt_me_route_drop_no_conn_total 26232
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 173
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 12
telemt_pool_force_close_total 135
telemt_pool_stale_pick_total 3052
telemt_me_writer_removed_total 1057
telemt_me_writer_removed_unexpected_total 727
telemt_me_refill_triggered_total 687
telemt_me_refill_skipped_inflight_total 40
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 65015
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 268636308 (256.19 MB)
telemt_user_octets_to_client{user="hello"} 7901500580 (7.36 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 12788.4 (3h 33m)
telemt_connections_total 99335
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 9661
telemt_me_keepalive_sent_total 14384
telemt_me_keepalive_pong_total 14374
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 622
telemt_me_reconnect_success_total 673
telemt_me_route_drop_no_conn_total 35850
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 192
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 13
telemt_pool_force_close_total 224
telemt_pool_stale_pick_total 3562
telemt_me_writer_removed_total 998
telemt_me_writer_removed_unexpected_total 641
telemt_me_refill_triggered_total 605
telemt_me_refill_skipped_inflight_total 36
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 596
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 88173
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 2341803216 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 31878029536 (29.69 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 10031.9 (2h 47m)
telemt_connections_total 121
telemt_connections_bad_total 26
telemt_me_keepalive_sent_total 10793
telemt_me_keepalive_pong_total 10781
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 3113
telemt_me_reconnect_success_total 3247
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 10
telemt_pool_force_close_total 31
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 3456
telemt_me_writer_removed_unexpected_total 3204
telemt_me_refill_triggered_total 3111
telemt_me_refill_skipped_inflight_total 93
telemt_me_writer_restored_same_endpoint_total 3110
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello1"} 95
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 328176 (320.48 KB)
telemt_user_octets_to_client{user="hello1"} 1449176 (1.38 MB)
```