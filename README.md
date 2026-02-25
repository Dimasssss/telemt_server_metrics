# Server Metrics 2026-02-25 23:08:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 624.0 (0h 10m)
telemt_connections_total 5640
telemt_handshake_timeouts_total 140
telemt_me_keepalive_sent_total 597
telemt_me_keepalive_pong_total 597
telemt_me_reconnect_attempts_total 16
telemt_me_reconnect_success_total 37
telemt_me_route_drop_no_conn_total 532
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_total 21
telemt_me_writer_removed_unexpected_total 21
telemt_me_refill_triggered_total 16
telemt_me_refill_skipped_inflight_total 5
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 5257
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 13640228 (13.01 MB)
telemt_user_octets_to_client{user="hello"} 1228405404 (1.14 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 1418.1 (0h 23m)
telemt_connections_total 5255
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 215
telemt_me_keepalive_sent_total 1491
telemt_me_keepalive_pong_total 1491
telemt_me_reconnect_attempts_total 69
telemt_me_reconnect_success_total 90
telemt_me_route_drop_no_conn_total 1015
telemt_desync_total 11
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_pool_force_close_total 8
telemt_pool_stale_pick_total 235
telemt_me_writer_removed_total 98
telemt_me_writer_removed_unexpected_total 69
telemt_me_refill_triggered_total 64
telemt_me_refill_skipped_inflight_total 5
telemt_me_writer_restored_same_endpoint_total 62
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 4943
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 20735788 (19.78 MB)
telemt_user_octets_to_client{user="hello"} 1304903336 (1.22 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 9145.8 (2h 32m)
telemt_connections_total 64112
telemt_connections_bad_total 1339
telemt_handshake_timeouts_total 15745
telemt_me_keepalive_sent_total 9960
telemt_me_keepalive_pong_total 9955
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 514
telemt_me_reconnect_success_total 562
telemt_me_route_drop_no_conn_total 11875
telemt_desync_total 156
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 9
telemt_pool_force_close_total 104
telemt_pool_stale_pick_total 1648
telemt_me_writer_removed_total 779
telemt_me_writer_removed_unexpected_total 526
telemt_me_refill_triggered_total 503
telemt_me_refill_skipped_inflight_total 23
telemt_me_writer_restored_same_endpoint_total 500
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 45361
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 380666676 (363.03 MB)
telemt_user_octets_to_client{user="hello"} 12843628076 (11.96 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 11551.2 (3h 12m)
telemt_connections_total 75521
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 8035
telemt_me_keepalive_sent_total 12920
telemt_me_keepalive_pong_total 12911
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 653
telemt_me_reconnect_success_total 711
telemt_me_route_drop_no_conn_total 25929
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 168
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 11
telemt_pool_force_close_total 128
telemt_pool_stale_pick_total 2862
telemt_me_writer_removed_total 976
telemt_me_writer_removed_unexpected_total 672
telemt_me_refill_triggered_total 633
telemt_me_refill_skipped_inflight_total 39
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 630
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 61488
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 263779548 (251.56 MB)
telemt_user_octets_to_client{user="hello"} 7451346420 (6.94 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 11863.9 (3h 17m)
telemt_connections_total 94893
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 9307
telemt_me_keepalive_sent_total 13354
telemt_me_keepalive_pong_total 13344
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 561
telemt_me_reconnect_success_total 602
telemt_me_route_drop_no_conn_total 34931
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 190
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 12
telemt_pool_force_close_total 206
telemt_pool_stale_pick_total 3342
telemt_me_writer_removed_total 902
telemt_me_writer_removed_unexpected_total 574
telemt_me_refill_triggered_total 547
telemt_me_refill_skipped_inflight_total 27
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 538
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 84152
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 2300090588 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 30396635396 (28.31 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 9107.6 (2h 31m)
telemt_connections_total 117
telemt_connections_bad_total 26
telemt_me_keepalive_sent_total 9818
telemt_me_keepalive_pong_total 9806
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 2824
telemt_me_reconnect_success_total 2955
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 9
telemt_pool_force_close_total 28
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 3142
telemt_me_writer_removed_unexpected_total 2914
telemt_me_refill_triggered_total 2822
telemt_me_refill_skipped_inflight_total 92
telemt_me_writer_restored_same_endpoint_total 2821
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello1"} 91
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 315348 (307.96 KB)
telemt_user_octets_to_client{user="hello1"} 1437120 (1.37 MB)
```