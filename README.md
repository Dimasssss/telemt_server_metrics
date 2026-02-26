# Server Metrics 2026-02-26 02:07:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 11409.9 (3h 10m)
telemt_connections_total 89805
telemt_connections_bad_total 629
telemt_handshake_timeouts_total 4888
telemt_me_keepalive_sent_total 12323
telemt_me_keepalive_pong_total 12321
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 434
telemt_me_reconnect_success_total 472
telemt_me_route_drop_no_conn_total 12899
telemt_desync_total 45
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 12
telemt_pool_drain_active 14
telemt_pool_force_close_total 125
telemt_pool_stale_pick_total 2997
telemt_me_writer_removed_total 761
telemt_me_writer_removed_unexpected_total 447
telemt_me_refill_triggered_total 428
telemt_me_refill_skipped_inflight_total 19
telemt_me_writer_restored_same_endpoint_total 425
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 79585
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 351366604 (335.09 MB)
telemt_user_octets_to_client{user="hello"} 12994926076 (12.10 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 12204.2 (3h 23m)
telemt_connections_total 48228
telemt_connections_bad_total 1408
telemt_handshake_timeouts_total 3739
telemt_me_keepalive_sent_total 13499
telemt_me_keepalive_pong_total 13496
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 724
telemt_me_reconnect_success_total 793
telemt_me_route_drop_no_conn_total 6643
telemt_desync_total 13
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 12
telemt_pool_force_close_total 129
telemt_pool_stale_pick_total 1591
telemt_me_writer_removed_total 1080
telemt_me_writer_removed_unexpected_total 747
telemt_me_refill_triggered_total 715
telemt_me_refill_skipped_inflight_total 32
telemt_me_writer_restored_same_endpoint_total 712
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 38727
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 112149024 (106.95 MB)
telemt_user_octets_to_client{user="hello"} 9269948856 (8.63 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 19931.6 (5h 32m)
telemt_connections_total 91186
telemt_connections_bad_total 1364
telemt_handshake_timeouts_total 17925
telemt_me_keepalive_sent_total 21706
telemt_me_keepalive_pong_total 21697
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1635
telemt_me_reconnect_success_total 1739
telemt_me_route_drop_no_conn_total 16723
telemt_desync_total 176
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 21
telemt_pool_drain_active 12
telemt_pool_force_close_total 202
telemt_pool_stale_pick_total 2444
telemt_me_writer_removed_total 2261
telemt_me_writer_removed_unexpected_total 1675
telemt_me_refill_triggered_total 1621
telemt_me_refill_skipped_inflight_total 54
telemt_me_writer_restored_same_endpoint_total 1617
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 69482
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 554551148 (528.86 MB)
telemt_user_octets_to_client{user="hello"} 19101308848 (17.79 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 22337.4 (6h 12m)
telemt_connections_total 124519
telemt_connections_bad_total 1136
telemt_handshake_timeouts_total 8902
telemt_me_keepalive_sent_total 25041
telemt_me_keepalive_pong_total 25026
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 1258
telemt_me_reconnect_success_total 1356
telemt_me_route_drop_no_conn_total 31722
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 239
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 23
telemt_pool_force_close_total 251
telemt_pool_stale_pick_total 4856
telemt_me_writer_removed_total 1931
telemt_me_writer_removed_unexpected_total 1299
telemt_me_refill_triggered_total 1233
telemt_me_refill_skipped_inflight_total 66
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1227
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 103923
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 368122260 (351.07 MB)
telemt_user_octets_to_client{user="hello"} 13989318816 (13.03 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 22650.1 (6h 17m)
telemt_connections_total 147902
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 14240
telemt_me_keepalive_sent_total 25076
telemt_me_keepalive_pong_total 25055
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 1118
telemt_me_reconnect_success_total 1221
telemt_me_route_drop_no_conn_total 44076
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 222
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 23
telemt_pool_force_close_total 350
telemt_pool_stale_pick_total 5362
telemt_me_writer_removed_total 1814
telemt_me_writer_removed_unexpected_total 1174
telemt_me_refill_triggered_total 1098
telemt_me_refill_skipped_inflight_total 76
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 1087
telemt_me_writer_restored_fallback_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 131429
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 2962103156 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 43458548348 (40.47 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 19893.6 (5h 31m)
telemt_connections_total 187
telemt_connections_bad_total 48
telemt_me_keepalive_sent_total 21368
telemt_me_keepalive_pong_total 21342
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 6166
telemt_me_reconnect_success_total 6396
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 21
telemt_pool_drain_active 3
telemt_pool_force_close_total 62
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 6862
telemt_me_writer_removed_unexpected_total 6334
telemt_me_refill_triggered_total 6161
telemt_me_refill_skipped_inflight_total 173
telemt_me_writer_restored_same_endpoint_total 6159
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello1"} 137
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 464096 (453.22 KB)
telemt_user_octets_to_client{user="hello1"} 1799908 (1.72 MB)
```