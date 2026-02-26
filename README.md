# Server Metrics 2026-02-26 19:07:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 72597.6 (20h 9m)
telemt_connections_total 1536998
telemt_connections_bad_total 7200
telemt_handshake_timeouts_total 261253
telemt_me_keepalive_sent_total 79579
telemt_me_keepalive_pong_total 79516
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 1996
telemt_me_reconnect_success_total 2133
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 441861
telemt_me_route_drop_channel_closed_total 6
telemt_desync_total 2540
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 1605
telemt_desync_frames_bucket_total{bucket="1_2"} 862
telemt_desync_frames_bucket_total{bucket="3_10"} 937
telemt_desync_frames_bucket_total{bucket="gt_10"} 741
telemt_pool_swap_total 76
telemt_pool_force_close_total 1203
telemt_pool_stale_pick_total 42860
telemt_me_writer_removed_total 4151
telemt_me_writer_removed_unexpected_total 2041
telemt_me_refill_triggered_total 1915
telemt_me_refill_skipped_inflight_total 126
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1892
telemt_me_writer_restored_fallback_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1198549
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 10439389416 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 326212845148 (303.81 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 40891.3 (11h 21m)
telemt_connections_total 370126
telemt_connections_bad_total 6774
telemt_handshake_timeouts_total 54457
telemt_me_keepalive_sent_total 45545
telemt_me_keepalive_pong_total 45513
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 1790
telemt_me_reconnect_success_total 1875
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 112884
telemt_desync_total 846
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 278
telemt_pool_swap_total 42
telemt_pool_force_close_total 649
telemt_pool_stale_pick_total 13166
telemt_me_writer_removed_total 2959
telemt_me_writer_removed_unexpected_total 1836
telemt_me_refill_triggered_total 1752
telemt_me_refill_skipped_inflight_total 84
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1742
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 293572
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 5169635116 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 90448808428 (84.24 GB)
```

## server3

```
telemt 3.1.2

telemt_uptime_seconds 396.9 (0h 6m)
telemt_connections_total 5127
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 447
telemt_me_keepalive_sent_total 1050
telemt_me_keepalive_pong_total 1049
telemt_me_reconnect_attempts_total 16
telemt_me_reconnect_success_total 39
telemt_me_route_drop_no_conn_total 1291
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_me_writer_removed_total 19
telemt_me_writer_removed_unexpected_total 19
telemt_me_refill_triggered_total 16
telemt_me_refill_skipped_inflight_total 3
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 4443
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 20144856 (19.21 MB)
telemt_user_octets_to_client{user="hello"} 1994915224 (1.86 GB)
```

## server4

```
telemt 3.1.2

telemt_uptime_seconds 1568.8 (0h 26m)
telemt_connections_total 13955
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 1381
telemt_me_keepalive_sent_total 4363
telemt_me_keepalive_pong_total 4359
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 64
telemt_me_reconnect_success_total 88
telemt_me_route_drop_no_conn_total 3585
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 595
telemt_me_writer_removed_total 95
telemt_me_writer_removed_unexpected_total 65
telemt_me_refill_triggered_total 54
telemt_me_refill_skipped_inflight_total 11
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 12216
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 90135648 (85.96 MB)
telemt_user_octets_to_client{user="hello"} 2558937524 (2.38 GB)
```

## server5

```
telemt 3.1.2

telemt_uptime_seconds 1925.6 (0h 32m)
telemt_connections_total 35788
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 5001
telemt_me_keepalive_sent_total 3801
telemt_me_keepalive_pong_total 3798
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 35
telemt_me_reconnect_success_total 58
telemt_me_route_drop_no_conn_total 9412
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 40
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_pool_drain_active 21
telemt_pool_force_close_total 23
telemt_pool_stale_pick_total 1197
telemt_me_writer_removed_total 72
telemt_me_writer_removed_unexpected_total 37
telemt_me_refill_triggered_total 31
telemt_me_refill_skipped_inflight_total 6
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 29422
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 255471440 (243.64 MB)
telemt_user_octets_to_client{user="hello"} 14482375796 (13.49 GB)
```

## reserve server

```
telemt 3.1.2

telemt_uptime_seconds 1575.3 (0h 26m)
telemt_connections_total 41
telemt_connections_bad_total 2
telemt_me_keepalive_sent_total 6917
telemt_me_keepalive_pong_total 6906
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 403
telemt_me_reconnect_success_total 445
telemt_pool_swap_total 1
telemt_pool_force_close_total 4
telemt_me_writer_removed_total 451
telemt_me_writer_removed_unexpected_total 418
telemt_me_refill_triggered_total 396
telemt_me_refill_skipped_inflight_total 22
telemt_me_writer_restored_same_endpoint_total 396
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello1"} 39
telemt_user_connections_current{user="hello1"} 6
telemt_user_octets_from_client{user="hello1"} 74496 (72.75 KB)
telemt_user_octets_to_client{user="hello1"} 3748368 (3.57 MB)
```