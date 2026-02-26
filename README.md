# Server Metrics 2026-02-26 19:02:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 72289.0 (20h 4m)
telemt_connections_total 1530953
telemt_connections_bad_total 7200
telemt_handshake_timeouts_total 259647
telemt_me_keepalive_sent_total 79270
telemt_me_keepalive_pong_total 79207
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 1985
telemt_me_reconnect_success_total 2121
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 440230
telemt_me_route_drop_channel_closed_total 6
telemt_desync_total 2534
telemt_desync_full_logged_total 932
telemt_desync_suppressed_total 1602
telemt_desync_frames_bucket_total{bucket="1_2"} 861
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 737
telemt_pool_swap_total 76
telemt_pool_force_close_total 1203
telemt_pool_stale_pick_total 42860
telemt_me_writer_removed_total 4140
telemt_me_writer_removed_unexpected_total 2030
telemt_me_refill_triggered_total 1904
telemt_me_refill_skipped_inflight_total 126
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1881
telemt_me_writer_restored_fallback_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1194254
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 10404274828 (9.69 GB)
telemt_user_octets_to_client{user="hello"} 324418186684 (302.14 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 40582.7 (11h 16m)
telemt_connections_total 367369
telemt_connections_bad_total 6774
telemt_handshake_timeouts_total 54026
telemt_me_keepalive_sent_total 45232
telemt_me_keepalive_pong_total 45199
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 1784
telemt_me_reconnect_success_total 1869
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 112061
telemt_desync_total 828
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 581
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 307
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 42
telemt_pool_force_close_total 649
telemt_pool_stale_pick_total 13166
telemt_me_writer_removed_total 2953
telemt_me_writer_removed_unexpected_total 1830
telemt_me_refill_triggered_total 1746
telemt_me_refill_skipped_inflight_total 84
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 1736
telemt_me_writer_restored_fallback_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 291345
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 5148959892 (4.80 GB)
telemt_user_octets_to_client{user="hello"} 89953445836 (83.78 GB)
```

## server3

```
telemt 3.1.2

telemt_uptime_seconds 88.2 (0h 1m)
telemt_connections_total 1418
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 26
telemt_me_keepalive_sent_total 217
telemt_me_keepalive_pong_total 215
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 201
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_user_connections_total{user="hello"} 1269
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 7639544 (7.29 MB)
telemt_user_octets_to_client{user="hello"} 408070444 (389.17 MB)
```

## server4

```
telemt 3.1.2

telemt_uptime_seconds 1260.3 (0h 21m)
telemt_connections_total 11030
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 552
telemt_me_keepalive_sent_total 3496
telemt_me_keepalive_pong_total 3492
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 50
telemt_me_reconnect_success_total 74
telemt_me_route_drop_no_conn_total 2735
telemt_desync_total 18
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 1
telemt_pool_force_close_total 17
telemt_pool_stale_pick_total 595
telemt_me_writer_removed_total 81
telemt_me_writer_removed_unexpected_total 51
telemt_me_refill_triggered_total 44
telemt_me_refill_skipped_inflight_total 7
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 10101
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 76420376 (72.88 MB)
telemt_user_octets_to_client{user="hello"} 2027344548 (1.89 GB)
```

## server5

```
telemt 3.1.2

telemt_uptime_seconds 1616.9 (0h 26m)
telemt_connections_total 29160
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 2897
telemt_me_keepalive_sent_total 3144
telemt_me_keepalive_pong_total 3143
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 47
telemt_me_route_drop_no_conn_total 7946
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 40
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 1
telemt_pool_force_close_total 23
telemt_pool_stale_pick_total 553
telemt_me_writer_removed_total 55
telemt_me_writer_removed_unexpected_total 26
telemt_me_refill_triggered_total 22
telemt_me_refill_skipped_inflight_total 4
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 25229
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 204204624 (194.74 MB)
telemt_user_octets_to_client{user="hello"} 11288309628 (10.51 GB)
```

## reserve server

```
telemt 3.1.2

telemt_uptime_seconds 1266.7 (0h 21m)
telemt_connections_total 40
telemt_connections_bad_total 1
telemt_me_keepalive_sent_total 5573
telemt_me_keepalive_pong_total 5568
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 311
telemt_me_reconnect_success_total 348
telemt_pool_swap_total 1
telemt_pool_force_close_total 4
telemt_me_writer_removed_total 352
telemt_me_writer_removed_unexpected_total 319
telemt_me_refill_triggered_total 304
telemt_me_refill_skipped_inflight_total 15
telemt_me_writer_restored_same_endpoint_total 304
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello1"} 39
telemt_user_connections_current{user="hello1"} 6
telemt_user_octets_from_client{user="hello1"} 70168 (68.52 KB)
telemt_user_octets_to_client{user="hello1"} 3745780 (3.57 MB)
```