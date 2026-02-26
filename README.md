# Server Metrics 2026-02-26 02:23:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 12333.7 (3h 25m)
telemt_connections_total 95979
telemt_connections_bad_total 629
telemt_handshake_timeouts_total 6643
telemt_me_keepalive_sent_total 13338
telemt_me_keepalive_pong_total 13336
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 458
telemt_me_reconnect_success_total 497
telemt_me_route_drop_no_conn_total 13755
telemt_desync_total 46
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 13
telemt_pool_drain_active 17
telemt_pool_force_close_total 139
telemt_pool_stale_pick_total 3119
telemt_me_writer_removed_total 811
telemt_me_writer_removed_unexpected_total 471
telemt_me_refill_triggered_total 452
telemt_me_refill_skipped_inflight_total 19
telemt_me_writer_restored_same_endpoint_total 449
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 83947
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 396180508 (377.83 MB)
telemt_user_octets_to_client{user="hello"} 14123338060 (13.15 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 13127.9 (3h 38m)
telemt_connections_total 51832
telemt_connections_bad_total 1417
telemt_handshake_timeouts_total 4192
telemt_me_keepalive_sent_total 14572
telemt_me_keepalive_pong_total 14569
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 796
telemt_me_reconnect_success_total 872
telemt_me_route_drop_no_conn_total 7107
telemt_desync_total 13
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 13
telemt_pool_force_close_total 149
telemt_pool_stale_pick_total 1759
telemt_me_writer_removed_total 1182
telemt_me_writer_removed_unexpected_total 822
telemt_me_refill_triggered_total 786
telemt_me_refill_skipped_inflight_total 36
telemt_me_writer_restored_same_endpoint_total 783
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 41694
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 121179376 (115.57 MB)
telemt_user_octets_to_client{user="hello"} 9568762088 (8.91 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 20855.3 (5h 47m)
telemt_connections_total 92949
telemt_connections_bad_total 1364
telemt_handshake_timeouts_total 18103
telemt_me_keepalive_sent_total 22729
telemt_me_keepalive_pong_total 22720
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1791
telemt_me_reconnect_success_total 1905
telemt_me_route_drop_no_conn_total 17140
telemt_desync_total 179
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 22
telemt_pool_drain_active 9
telemt_pool_force_close_total 214
telemt_pool_stale_pick_total 2505
telemt_me_writer_removed_total 2456
telemt_me_writer_removed_unexpected_total 1838
telemt_me_refill_triggered_total 1776
telemt_me_refill_skipped_inflight_total 62
telemt_me_writer_restored_same_endpoint_total 1771
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 71041
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 559902732 (533.96 MB)
telemt_user_octets_to_client{user="hello"} 19299902048 (17.97 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 23261.2 (6h 27m)
telemt_connections_total 129031
telemt_connections_bad_total 1137
telemt_handshake_timeouts_total 9128
telemt_me_keepalive_sent_total 26003
telemt_me_keepalive_pong_total 25987
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 1264
telemt_me_reconnect_success_total 1363
telemt_me_route_drop_no_conn_total 32352
telemt_me_route_drop_channel_closed_total 2
telemt_desync_total 239
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 24
telemt_pool_force_close_total 260
telemt_pool_stale_pick_total 5009
telemt_me_writer_removed_total 1964
telemt_me_writer_removed_unexpected_total 1305
telemt_me_refill_triggered_total 1239
telemt_me_refill_skipped_inflight_total 66
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1233
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 107773
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 376855980 (359.40 MB)
telemt_user_octets_to_client{user="hello"} 14727318520 (13.72 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 23573.7 (6h 32m)
telemt_connections_total 154146
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 15043
telemt_me_keepalive_sent_total 26079
telemt_me_keepalive_pong_total 26058
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 1120
telemt_me_reconnect_success_total 1224
telemt_me_route_drop_no_conn_total 45171
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 226
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 24
telemt_pool_force_close_total 366
telemt_pool_stale_pick_total 5562
telemt_me_writer_removed_total 1843
telemt_me_writer_removed_unexpected_total 1176
telemt_me_refill_triggered_total 1100
telemt_me_refill_skipped_inflight_total 76
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 1089
telemt_me_writer_restored_fallback_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 136573
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 2985508888 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 44616606208 (41.55 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 20817.2 (5h 46m)
telemt_connections_total 191
telemt_connections_bad_total 48
telemt_me_keepalive_sent_total 22333
telemt_me_keepalive_pong_total 22306
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 6458
telemt_me_reconnect_success_total 6695
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 22
telemt_pool_drain_active 3
telemt_pool_force_close_total 65
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 7182
telemt_me_writer_removed_unexpected_total 6631
telemt_me_refill_triggered_total 6453
telemt_me_refill_skipped_inflight_total 178
telemt_me_writer_restored_same_endpoint_total 6451
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello1"} 141
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 475992 (464.84 KB)
telemt_user_octets_to_client{user="hello1"} 1806200 (1.72 MB)
```