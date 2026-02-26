# Server Metrics 2026-02-26 03:25:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 16032.8 (4h 27m)
telemt_connections_total 124078
telemt_connections_bad_total 991
telemt_handshake_timeouts_total 9750
telemt_me_keepalive_sent_total 17359
telemt_me_keepalive_pong_total 17357
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 532
telemt_me_reconnect_success_total 585
telemt_me_route_drop_no_conn_total 18680
telemt_desync_total 53
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 16
telemt_pool_force_close_total 199
telemt_pool_stale_pick_total 3685
telemt_me_writer_removed_total 996
telemt_me_writer_removed_unexpected_total 554
telemt_me_refill_triggered_total 525
telemt_me_refill_skipped_inflight_total 29
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 107840
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 582272640 (555.30 MB)
telemt_user_octets_to_client{user="hello"} 19997988128 (18.62 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 16827.1 (4h 40m)
telemt_connections_total 65288
telemt_connections_bad_total 1455
telemt_handshake_timeouts_total 6691
telemt_me_keepalive_sent_total 18936
telemt_me_keepalive_pong_total 18931
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 1156
telemt_me_reconnect_success_total 1238
telemt_me_route_drop_no_conn_total 9521
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 33
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 17
telemt_pool_force_close_total 185
telemt_pool_stale_pick_total 2392
telemt_me_writer_removed_total 1655
telemt_me_writer_removed_unexpected_total 1182
telemt_me_refill_triggered_total 1143
telemt_me_refill_skipped_inflight_total 39
telemt_me_writer_restored_same_endpoint_total 1138
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 51489
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 179775556 (171.45 MB)
telemt_user_octets_to_client{user="hello"} 11409244204 (10.63 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 24554.8 (6h 49m)
telemt_connections_total 101795
telemt_connections_bad_total 1370
telemt_handshake_timeouts_total 19273
telemt_me_keepalive_sent_total 26810
telemt_me_keepalive_pong_total 26799
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 2311
telemt_me_reconnect_success_total 2443
telemt_me_route_drop_no_conn_total 18913
telemt_desync_total 210
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 25
telemt_pool_force_close_total 245
telemt_pool_stale_pick_total 2744
telemt_me_writer_removed_total 3078
telemt_me_writer_removed_unexpected_total 2366
telemt_me_refill_triggered_total 2295
telemt_me_refill_skipped_inflight_total 71
telemt_me_writer_restored_same_endpoint_total 2290
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 78553
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 601635832 (573.76 MB)
telemt_user_octets_to_client{user="hello"} 20601282288 (19.19 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 26960.4 (7h 29m)
telemt_connections_total 141605
telemt_connections_bad_total 1592
telemt_handshake_timeouts_total 9811
telemt_me_keepalive_sent_total 29996
telemt_me_keepalive_pong_total 29979
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 1423
telemt_me_reconnect_success_total 1539
telemt_me_route_drop_no_conn_total 34557
telemt_me_route_drop_channel_closed_total 2
telemt_desync_total 251
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 27
telemt_pool_force_close_total 288
telemt_pool_stale_pick_total 5344
telemt_me_writer_removed_total 2220
telemt_me_writer_removed_unexpected_total 1476
telemt_me_refill_triggered_total 1396
telemt_me_refill_skipped_inflight_total 80
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1389
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 118273
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 420728232 (401.24 MB)
telemt_user_octets_to_client{user="hello"} 15285073944 (14.24 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 27273.0 (7h 34m)
telemt_connections_total 170080
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 15859
telemt_me_keepalive_sent_total 30172
telemt_me_keepalive_pong_total 30148
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1249
telemt_me_reconnect_success_total 1362
telemt_me_route_drop_no_conn_total 49274
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 259
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 28
telemt_pool_force_close_total 414
telemt_pool_stale_pick_total 6221
telemt_me_writer_removed_total 2087
telemt_me_writer_removed_unexpected_total 1310
telemt_me_refill_triggered_total 1228
telemt_me_refill_skipped_inflight_total 82
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 1217
telemt_me_writer_restored_fallback_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 151187
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 3135340608 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 49273852380 (45.89 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 24516.4 (6h 48m)
telemt_connections_total 237
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 1
telemt_me_keepalive_sent_total 26297
telemt_me_keepalive_pong_total 26264
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 7619
telemt_me_reconnect_success_total 7895
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 25
telemt_pool_force_close_total 78
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 8453
telemt_me_writer_removed_unexpected_total 7822
telemt_me_refill_triggered_total 7614
telemt_me_refill_skipped_inflight_total 208
telemt_me_writer_restored_same_endpoint_total 7612
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello1"} 157
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 530292 (517.86 KB)
telemt_user_octets_to_client{user="hello1"} 2078568 (1.98 MB)
```