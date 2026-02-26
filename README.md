# Server Metrics 2026-02-26 03:35:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 16655.6 (4h 37m)
telemt_connections_total 129415
telemt_connections_bad_total 1003
telemt_handshake_timeouts_total 10062
telemt_me_keepalive_sent_total 18045
telemt_me_keepalive_pong_total 18043
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 559
telemt_me_reconnect_success_total 615
telemt_me_route_drop_no_conn_total 19871
telemt_desync_total 54
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 17
telemt_pool_force_close_total 213
telemt_pool_stale_pick_total 3925
telemt_me_writer_removed_total 1053
telemt_me_writer_removed_unexpected_total 583
telemt_me_refill_triggered_total 552
telemt_me_refill_skipped_inflight_total 31
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 112717
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 616385700 (587.83 MB)
telemt_user_octets_to_client{user="hello"} 21089511120 (19.64 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 17449.9 (4h 50m)
telemt_connections_total 67677
telemt_connections_bad_total 1456
telemt_handshake_timeouts_total 7107
telemt_me_keepalive_sent_total 19664
telemt_me_keepalive_pong_total 19658
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 1214
telemt_me_reconnect_success_total 1298
telemt_me_route_drop_no_conn_total 10070
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 36
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 18
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2645
telemt_me_writer_removed_total 1739
telemt_me_writer_removed_unexpected_total 1241
telemt_me_refill_triggered_total 1201
telemt_me_refill_skipped_inflight_total 40
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 53276
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 188884636 (180.13 MB)
telemt_user_octets_to_client{user="hello"} 11589635036 (10.79 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 25177.3 (6h 59m)
telemt_connections_total 103932
telemt_connections_bad_total 1371
telemt_handshake_timeouts_total 19551
telemt_me_keepalive_sent_total 27488
telemt_me_keepalive_pong_total 27477
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 2361
telemt_me_reconnect_success_total 2493
telemt_me_route_drop_no_conn_total 19352
telemt_desync_total 217
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 26
telemt_pool_force_close_total 253
telemt_pool_stale_pick_total 2782
telemt_me_writer_removed_total 3157
telemt_me_writer_removed_unexpected_total 2416
telemt_me_refill_triggered_total 2345
telemt_me_refill_skipped_inflight_total 71
telemt_me_writer_restored_same_endpoint_total 2340
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 80387
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 619609560 (590.91 MB)
telemt_user_octets_to_client{user="hello"} 20996954204 (19.55 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 27582.9 (7h 39m)
telemt_connections_total 145607
telemt_connections_bad_total 2917
telemt_handshake_timeouts_total 9849
telemt_me_keepalive_sent_total 30655
telemt_me_keepalive_pong_total 30638
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 1462
telemt_me_reconnect_success_total 1584
telemt_me_route_drop_no_conn_total 35026
telemt_me_route_drop_channel_closed_total 2
telemt_desync_total 251
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 28
telemt_pool_force_close_total 296
telemt_pool_stale_pick_total 5497
telemt_me_writer_removed_total 2290
telemt_me_writer_removed_unexpected_total 1520
telemt_me_refill_triggered_total 1435
telemt_me_refill_skipped_inflight_total 85
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1428
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 120596
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 431110228 (411.14 MB)
telemt_user_octets_to_client{user="hello"} 15712377920 (14.63 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 27895.6 (7h 44m)
telemt_connections_total 172752
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 16142
telemt_me_keepalive_sent_total 30879
telemt_me_keepalive_pong_total 30854
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1284
telemt_me_reconnect_success_total 1399
telemt_me_route_drop_no_conn_total 49962
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 262
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 115
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 29
telemt_pool_force_close_total 426
telemt_pool_stale_pick_total 6326
telemt_me_writer_removed_total 2151
telemt_me_writer_removed_unexpected_total 1347
telemt_me_refill_triggered_total 1263
telemt_me_refill_skipped_inflight_total 84
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 1252
telemt_me_writer_restored_fallback_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 153530
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 3147455312 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 50040594452 (46.60 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 25139.3 (6h 58m)
telemt_connections_total 241
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 1
telemt_me_keepalive_sent_total 27059
telemt_me_keepalive_pong_total 27027
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 7831
telemt_me_reconnect_success_total 8108
telemt_me_seq_mismatch_total 18
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 26
telemt_pool_force_close_total 81
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 8687
telemt_me_writer_removed_unexpected_total 8034
telemt_me_refill_triggered_total 7826
telemt_me_refill_skipped_inflight_total 208
telemt_me_writer_restored_same_endpoint_total 7824
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello1"} 161
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 542648 (529.93 KB)
telemt_user_octets_to_client{user="hello1"} 2087024 (1.99 MB)
```