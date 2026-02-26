# Server Metrics 2026-02-26 00:30:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 5552.4 (1h 32m)
telemt_connections_total 47654
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 2092
telemt_me_keepalive_sent_total 6122
telemt_me_keepalive_pong_total 6122
telemt_me_reconnect_attempts_total 286
telemt_me_reconnect_success_total 317
telemt_me_route_drop_no_conn_total 7202
telemt_desync_total 26
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 5
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 1577
telemt_me_writer_removed_total 433
telemt_me_writer_removed_unexpected_total 297
telemt_me_refill_triggered_total 283
telemt_me_refill_skipped_inflight_total 14
telemt_me_writer_restored_same_endpoint_total 281
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 43096
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 179533708 (171.22 MB)
telemt_user_octets_to_client{user="hello"} 7232779680 (6.74 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 6346.7 (1h 45m)
telemt_connections_total 24364
telemt_connections_bad_total 532
telemt_handshake_timeouts_total 1049
telemt_me_keepalive_sent_total 7012
telemt_me_keepalive_pong_total 7010
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 351
telemt_me_reconnect_success_total 399
telemt_me_route_drop_no_conn_total 3504
telemt_desync_total 13
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 6
telemt_pool_force_close_total 48
telemt_pool_stale_pick_total 866
telemt_me_writer_removed_total 535
telemt_me_writer_removed_unexpected_total 366
telemt_me_refill_triggered_total 345
telemt_me_refill_skipped_inflight_total 21
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 21118
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 58532480 (55.82 MB)
telemt_user_octets_to_client{user="hello"} 4102356684 (3.82 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 14074.2 (3h 54m)
telemt_connections_total 75626
telemt_connections_bad_total 1343
telemt_handshake_timeouts_total 16323
telemt_me_keepalive_sent_total 15320
telemt_me_keepalive_pong_total 15314
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 1041
telemt_me_reconnect_success_total 1122
telemt_me_route_drop_no_conn_total 13916
telemt_desync_total 162
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 14
telemt_pool_force_close_total 152
telemt_pool_stale_pick_total 1958
telemt_me_writer_removed_total 1468
telemt_me_writer_removed_unexpected_total 1075
telemt_me_refill_triggered_total 1030
telemt_me_refill_skipped_inflight_total 45
telemt_me_writer_restored_same_endpoint_total 1027
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 55855
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 460657476 (439.32 MB)
telemt_user_octets_to_client{user="hello"} 14825639428 (13.81 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 16479.8 (4h 34m)
telemt_connections_total 97655
telemt_connections_bad_total 1116
telemt_handshake_timeouts_total 8513
telemt_me_keepalive_sent_total 18462
telemt_me_keepalive_pong_total 18450
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 920
telemt_me_reconnect_success_total 1002
telemt_me_route_drop_no_conn_total 28352
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 224
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 17
telemt_pool_drain_active 11
telemt_pool_force_close_total 173
telemt_pool_stale_pick_total 3692
telemt_me_writer_removed_total 1413
telemt_me_writer_removed_unexpected_total 957
telemt_me_refill_triggered_total 899
telemt_me_refill_skipped_inflight_total 58
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 895
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 80055
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 304964596 (290.84 MB)
telemt_user_octets_to_client{user="hello"} 10145423492 (9.45 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 16792.4 (4h 39m)
telemt_connections_total 120271
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 11948
telemt_me_keepalive_sent_total 18741
telemt_me_keepalive_pong_total 18727
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 871
telemt_me_reconnect_success_total 950
telemt_me_route_drop_no_conn_total 39949
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 209
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 17
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 4303
telemt_me_writer_removed_total 1384
telemt_me_writer_removed_unexpected_total 912
telemt_me_refill_triggered_total 853
telemt_me_refill_skipped_inflight_total 59
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 844
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 106568
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 2767162124 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 38086309052 (35.47 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 14036.0 (3h 53m)
telemt_connections_total 153
telemt_connections_bad_total 40
telemt_me_keepalive_sent_total 15031
telemt_me_keepalive_pong_total 15012
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 4360
telemt_me_reconnect_success_total 4525
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 14
telemt_pool_force_close_total 43
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 4827
telemt_me_writer_removed_unexpected_total 4475
telemt_me_refill_triggered_total 4355
telemt_me_refill_skipped_inflight_total 120
telemt_me_writer_restored_same_endpoint_total 4353
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello1"} 113
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 383996 (375.00 KB)
telemt_user_octets_to_client{user="hello1"} 1498560 (1.43 MB)
```