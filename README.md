# Server Metrics 2026-02-25 23:13:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 932.1 (0h 15m)
telemt_connections_total 8195
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 229
telemt_me_keepalive_sent_total 902
telemt_me_keepalive_pong_total 902
telemt_me_reconnect_attempts_total 28
telemt_me_reconnect_success_total 52
telemt_me_route_drop_no_conn_total 873
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_stale_pick_total 200
telemt_me_writer_removed_total 36
telemt_me_writer_removed_unexpected_total 36
telemt_me_refill_triggered_total 28
telemt_me_refill_skipped_inflight_total 8
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 7588
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 18570612 (17.71 MB)
telemt_user_octets_to_client{user="hello"} 1601775072 (1.49 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 1726.4 (0h 28m)
telemt_connections_total 6674
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 345
telemt_me_keepalive_sent_total 1832
telemt_me_keepalive_pong_total 1832
telemt_me_reconnect_attempts_total 79
telemt_me_reconnect_success_total 102
telemt_me_route_drop_no_conn_total 1161
telemt_desync_total 11
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 8
telemt_pool_stale_pick_total 235
telemt_me_writer_removed_total 110
telemt_me_writer_removed_unexpected_total 81
telemt_me_refill_triggered_total 74
telemt_me_refill_skipped_inflight_total 7
telemt_me_writer_restored_same_endpoint_total 72
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 5870
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 22822012 (21.76 MB)
telemt_user_octets_to_client{user="hello"} 1355775920 (1.26 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 9453.9 (2h 37m)
telemt_connections_total 64914
telemt_connections_bad_total 1339
telemt_handshake_timeouts_total 15776
telemt_me_keepalive_sent_total 10295
telemt_me_keepalive_pong_total 10290
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 539
telemt_me_reconnect_success_total 587
telemt_me_route_drop_no_conn_total 12004
telemt_desync_total 159
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 9
telemt_pool_force_close_total 104
telemt_pool_stale_pick_total 1694
telemt_me_writer_removed_total 804
telemt_me_writer_removed_unexpected_total 551
telemt_me_refill_triggered_total 528
telemt_me_refill_skipped_inflight_total 23
telemt_me_writer_restored_same_endpoint_total 525
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 46117
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 384765772 (366.94 MB)
telemt_user_octets_to_client{user="hello"} 13055173476 (12.16 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 11859.4 (3h 17m)
telemt_connections_total 77033
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 8204
telemt_me_keepalive_sent_total 13278
telemt_me_keepalive_pong_total 13267
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 679
telemt_me_reconnect_success_total 739
telemt_me_route_drop_no_conn_total 26055
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 169
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 12
telemt_pool_force_close_total 135
telemt_pool_stale_pick_total 3052
telemt_me_writer_removed_total 1029
telemt_me_writer_removed_unexpected_total 699
telemt_me_refill_triggered_total 659
telemt_me_refill_skipped_inflight_total 40
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 656
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 62702
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 265528752 (253.23 MB)
telemt_user_octets_to_client{user="hello"} 7592005692 (7.07 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 12172.2 (3h 22m)
telemt_connections_total 96203
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 9475
telemt_me_keepalive_sent_total 13671
telemt_me_keepalive_pong_total 13661
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 569
telemt_me_reconnect_success_total 614
telemt_me_route_drop_no_conn_total 35150
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 191
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 12
telemt_pool_force_close_total 206
telemt_pool_stale_pick_total 3342
telemt_me_writer_removed_total 914
telemt_me_writer_removed_unexpected_total 586
telemt_me_refill_triggered_total 554
telemt_me_refill_skipped_inflight_total 32
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 546
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 85286
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 2314500968 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 30521015192 (28.42 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 9415.7 (2h 36m)
telemt_connections_total 117
telemt_connections_bad_total 26
telemt_me_keepalive_sent_total 10129
telemt_me_keepalive_pong_total 10117
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 2928
telemt_me_reconnect_success_total 3059
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 9
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 3246
telemt_me_writer_removed_unexpected_total 3018
telemt_me_refill_triggered_total 2926
telemt_me_refill_skipped_inflight_total 92
telemt_me_writer_restored_same_endpoint_total 2925
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello1"} 91
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 319396 (311.91 KB)
telemt_user_octets_to_client{user="hello1"} 1439244 (1.37 MB)
```