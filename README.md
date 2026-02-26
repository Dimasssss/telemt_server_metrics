# Server Metrics 2026-02-26 00:14:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.0

telemt_uptime_seconds 4628.3 (1h 17m)
telemt_connections_total 40629
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 1899
telemt_me_keepalive_sent_total 5085
telemt_me_keepalive_pong_total 5085
telemt_me_reconnect_attempts_total 233
telemt_me_reconnect_success_total 263
telemt_me_route_drop_no_conn_total 6273
telemt_desync_total 26
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 4
telemt_pool_force_close_total 45
telemt_pool_stale_pick_total 1315
telemt_me_writer_removed_total 354
telemt_me_writer_removed_unexpected_total 244
telemt_me_refill_triggered_total 230
telemt_me_refill_skipped_inflight_total 14
telemt_me_writer_restored_same_endpoint_total 228
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 36743
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 154142700 (147.00 MB)
telemt_user_octets_to_client{user="hello"} 5482606500 (5.11 GB)
```

## server2

```
telemt 3.1.0

telemt_uptime_seconds 5422.5 (1h 30m)
telemt_connections_total 20386
telemt_connections_bad_total 507
telemt_handshake_timeouts_total 710
telemt_me_keepalive_sent_total 5990
telemt_me_keepalive_pong_total 5988
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 290
telemt_me_reconnect_success_total 334
telemt_me_route_drop_no_conn_total 2998
telemt_desync_total 12
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 5
telemt_pool_force_close_total 38
telemt_pool_stale_pick_total 809
telemt_me_writer_removed_total 444
telemt_me_writer_removed_unexpected_total 304
telemt_me_refill_triggered_total 285
telemt_me_refill_skipped_inflight_total 19
telemt_me_writer_restored_same_endpoint_total 283
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 18334
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 47647704 (45.44 MB)
telemt_user_octets_to_client{user="hello"} 2785505040 (2.59 GB)
```

## server3

```
telemt 3.1.0

telemt_uptime_seconds 13149.8 (3h 39m)
telemt_connections_total 73454
telemt_connections_bad_total 1342
telemt_handshake_timeouts_total 16266
telemt_me_keepalive_sent_total 14283
telemt_me_keepalive_pong_total 14277
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 928
telemt_me_reconnect_success_total 1007
telemt_me_route_drop_no_conn_total 13699
telemt_desync_total 162
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 13
telemt_pool_force_close_total 143
telemt_pool_stale_pick_total 1914
telemt_me_writer_removed_total 1330
telemt_me_writer_removed_unexpected_total 961
telemt_me_refill_triggered_total 917
telemt_me_refill_skipped_inflight_total 44
telemt_me_writer_restored_same_endpoint_total 914
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 53924
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 446041540 (425.38 MB)
telemt_user_octets_to_client{user="hello"} 14485355000 (13.49 GB)
```

## server4

```
telemt 3.1.0

telemt_uptime_seconds 15555.6 (4h 19m)
telemt_connections_total 93677
telemt_connections_bad_total 659
telemt_handshake_timeouts_total 8465
telemt_me_keepalive_sent_total 17437
telemt_me_keepalive_pong_total 17426
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 873
telemt_me_reconnect_success_total 948
telemt_me_route_drop_no_conn_total 27887
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 224
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 16
telemt_pool_drain_active 11
telemt_pool_force_close_total 162
telemt_pool_stale_pick_total 3581
telemt_me_writer_removed_total 1331
telemt_me_writer_removed_unexpected_total 903
telemt_me_refill_triggered_total 852
telemt_me_refill_skipped_inflight_total 51
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 76941
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 298692280 (284.86 MB)
telemt_user_octets_to_client{user="hello"} 9517657736 (8.86 GB)
```

## server5

```
telemt 3.1.0

telemt_uptime_seconds 15868.4 (4h 24m)
telemt_connections_total 114662
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 11674
telemt_me_keepalive_sent_total 17748
telemt_me_keepalive_pong_total 17736
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 841
telemt_me_reconnect_success_total 919
telemt_me_route_drop_no_conn_total 39098
telemt_me_route_drop_channel_closed_total 1
telemt_desync_total 209
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 16
telemt_pool_force_close_total 268
telemt_pool_stale_pick_total 4098
telemt_me_writer_removed_total 1324
telemt_me_writer_removed_unexpected_total 881
telemt_me_refill_triggered_total 824
telemt_me_refill_skipped_inflight_total 57
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 815
telemt_me_writer_restored_fallback_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 101380
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 2740687332 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 36521896508 (34.01 GB)
```

## reserve server

```
telemt 3.1.0

telemt_uptime_seconds 13111.9 (3h 38m)
telemt_connections_total 144
telemt_connections_bad_total 35
telemt_me_keepalive_sent_total 14051
telemt_me_keepalive_pong_total 14035
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 4067
telemt_me_reconnect_success_total 4227
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 8
telemt_pool_swap_total 13
telemt_pool_force_close_total 40
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_total 4508
telemt_me_writer_removed_unexpected_total 4179
telemt_me_refill_triggered_total 4064
telemt_me_refill_skipped_inflight_total 115
telemt_me_writer_restored_same_endpoint_total 4063
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello1"} 109
telemt_user_connections_current{user="hello1"} 4
telemt_user_octets_from_client{user="hello1"} 369972 (361.30 KB)
telemt_user_octets_to_client{user="hello1"} 1486980 (1.42 MB)
```