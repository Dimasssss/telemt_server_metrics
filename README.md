# Server Metrics 2026-02-26 01:01:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 7405.6 (2h 3m)
telemt_connections_total 63780
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 2987
telemt_me_keepalive_sent_total 8067
telemt_me_keepalive_pong_total 8064
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 333
telemt_me_reconnect_success_total 365
telemt_me_route_drop_no_conn_total 8842
telemt_desync_total 29
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 7
telemt_pool_force_close_total 79
telemt_pool_stale_pick_total 2007
telemt_me_writer_removed_total 536
telemt_me_writer_removed_unexpected_total 344
telemt_me_refill_triggered_total 330
telemt_me_refill_skipped_inflight_total 14
telemt_me_writer_restored_same_endpoint_total 328
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 56842
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 256099652 (244.24 MB)
telemt_user_octets_to_client{user="hello"} 9774146052 (9.10 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 8199.8 (2h 16m)
telemt_connections_total 31906
telemt_connections_bad_total 587
telemt_handshake_timeouts_total 1886
telemt_me_keepalive_sent_total 9103
telemt_me_keepalive_pong_total 9101
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 466
telemt_me_reconnect_success_total 522
telemt_me_route_drop_no_conn_total 4416
telemt_desync_total 13
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 8
telemt_pool_force_close_total 80
telemt_pool_stale_pick_total 1080
telemt_me_writer_removed_total 710
telemt_me_writer_removed_unexpected_total 485
telemt_me_refill_triggered_total 459
telemt_me_refill_skipped_inflight_total 26
telemt_me_writer_restored_same_endpoint_total 457
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 26327
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 75266356 (71.78 MB)
telemt_user_octets_to_client{user="hello"} 6096159324 (5.68 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 15927.3 (4h 25m)
telemt_connections_total 80891
telemt_connections_bad_total 1344
telemt_handshake_timeouts_total 17307
telemt_me_keepalive_sent_total 17327
telemt_me_keepalive_pong_total 17319
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 1234
telemt_me_reconnect_success_total 1320
telemt_me_route_drop_no_conn_total 14672
telemt_desync_total 162
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 16
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 2058
telemt_me_writer_removed_total 1722
telemt_me_writer_removed_unexpected_total 1269
telemt_me_refill_triggered_total 1223
telemt_me_refill_skipped_inflight_total 46
telemt_me_writer_restored_same_endpoint_total 1220
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 60046
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 486640416 (464.10 MB)
telemt_user_octets_to_client{user="hello"} 15307581176 (14.26 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 18333.0 (5h 5m)
telemt_connections_total 105679
telemt_connections_bad_total 1132
telemt_handshake_timeouts_total 8646
telemt_me_keepalive_sent_total 20519
telemt_me_keepalive_pong_total 20506
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 1053
telemt_me_reconnect_success_total 1139
telemt_me_route_drop_no_conn_total 29166
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 224
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 19
telemt_pool_drain_active 14
telemt_pool_force_close_total 196
telemt_pool_stale_pick_total 4082
telemt_me_writer_removed_total 1599
telemt_me_writer_removed_unexpected_total 1091
telemt_me_refill_triggered_total 1032
telemt_me_refill_skipped_inflight_total 59
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1028
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 87170
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 319547504 (304.74 MB)
telemt_user_octets_to_client{user="hello"} 11672224784 (10.87 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 18645.6 (5h 10m)
telemt_connections_total 129761
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 12382
telemt_me_keepalive_sent_total 20735
telemt_me_keepalive_pong_total 20717
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 927
telemt_me_reconnect_success_total 1012
telemt_me_route_drop_no_conn_total 41547
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 214
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 19
telemt_pool_force_close_total 307
telemt_pool_stale_pick_total 4690
telemt_me_writer_removed_total 1499
telemt_me_writer_removed_unexpected_total 973
telemt_me_refill_triggered_total 908
telemt_me_refill_skipped_inflight_total 65
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 898
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 115342
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 2869303764 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 39487165016 (36.78 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 15889.1 (4h 24m)
telemt_connections_total 167
telemt_connections_bad_total 46
telemt_me_keepalive_sent_total 17018
telemt_me_keepalive_pong_total 16996
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 4924
telemt_me_reconnect_success_total 5107
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 16
telemt_pool_force_close_total 49
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 5456
telemt_me_writer_removed_unexpected_total 5053
telemt_me_refill_triggered_total 4919
telemt_me_refill_skipped_inflight_total 134
telemt_me_writer_restored_same_endpoint_total 4917
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello1"} 121
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 409328 (399.73 KB)
telemt_user_octets_to_client{user="hello1"} 1753728 (1.67 MB)
```