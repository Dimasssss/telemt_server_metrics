# Server Metrics 2026-03-04 13:25:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 58477.0 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1040396
telemt_connections_bad_total 13895
telemt_handshake_timeouts_total 16615
telemt_upstream_connect_attempt_total 34535
telemt_upstream_connect_success_total 34383
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 34383
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 385
telemt_me_reconnect_attempts_total 7207
telemt_me_reconnect_success_total 7154
telemt_me_reader_eof_total 7376
telemt_me_idle_close_by_peer_total 7375
telemt_me_route_drop_no_conn_total 373402
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 229
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1699
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1127
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7376
telemt_me_writer_restored_same_endpoint_total 7132
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 819730
telemt_user_connections_current{user="hello"} 1138
telemt_user_octets_from_client{user="hello"} 9317895140 (8.68 GB)
telemt_user_octets_to_client{user="hello"} 274078429080 (255.26 GB)
telemt_user_unique_ips_current{user="hello"} 99
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 58473.5 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405038
telemt_connections_bad_total 3318
telemt_handshake_timeouts_total 28969
telemt_upstream_connect_attempt_total 105313
telemt_upstream_connect_success_total 103711
telemt_upstream_connect_fail_total 763
telemt_upstream_connect_attempts_per_request{bucket="1"} 103705
telemt_upstream_connect_attempts_per_request{bucket="2"} 769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34863
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 763
telemt_me_keepalive_timeout_total 1435
telemt_me_reconnect_attempts_total 58027
telemt_me_reconnect_success_total 57934
telemt_me_reader_eof_total 59398
telemt_me_idle_close_by_peer_total 59397
telemt_me_route_drop_no_conn_total 164250
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 245
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 803
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 155
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 309
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 59478
telemt_me_writer_restored_same_endpoint_total 57909
telemt_me_writer_removed_unexpected_minus_restored_total 1569
telemt_user_connections_total{user="hello"} 311022
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 4049874308 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 98331138216 (91.58 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 58472.2 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787390
telemt_connections_bad_total 174099
telemt_handshake_timeouts_total 27668
telemt_upstream_connect_attempt_total 82254
telemt_upstream_connect_success_total 81741
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 81740
telemt_upstream_connect_attempts_per_request{bucket="2"} 248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 1071
telemt_me_reconnect_attempts_total 37762
telemt_me_reconnect_success_total 37666
telemt_me_reader_eof_total 39656
telemt_me_idle_close_by_peer_total 39652
telemt_me_route_drop_no_conn_total 289477
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 241
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1483
telemt_desync_full_logged_total 512
telemt_desync_suppressed_total 971
telemt_desync_frames_bucket_total{bucket="1_2"} 456
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 540
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39668
telemt_me_writer_restored_same_endpoint_total 37644
telemt_me_writer_removed_unexpected_minus_restored_total 2024
telemt_user_connections_total{user="hello"} 549149
telemt_user_connections_current{user="hello"} 654
telemt_user_octets_from_client{user="hello"} 11995311284 (11.17 GB)
telemt_user_octets_to_client{user="hello"} 183715038924 (171.10 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 5149.5 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63600
telemt_connections_bad_total 6064
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 1942
telemt_upstream_connect_success_total 1942
telemt_upstream_connect_attempts_per_request{bucket="1"} 1942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 738
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 140
telemt_me_reconnect_success_total 157
telemt_me_reader_eof_total 139
telemt_me_idle_close_by_peer_total 139
telemt_me_route_drop_no_conn_total 22231
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 71
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 139
telemt_me_writer_restored_same_endpoint_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 55533
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 1071999416 (1022.34 MB)
telemt_user_octets_to_client{user="hello"} 37092692572 (34.55 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 5508.9 (1h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100628
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 1526
telemt_upstream_connect_attempt_total 3261
telemt_upstream_connect_success_total 3245
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 3245
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 550
telemt_me_reconnect_success_total 562
telemt_me_reader_eof_total 556
telemt_me_idle_close_by_peer_total 556
telemt_me_route_drop_no_conn_total 32439
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 276
telemt_desync_full_logged_total 104
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 556
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 86336
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 907416992 (865.38 MB)
telemt_user_octets_to_client{user="hello"} 23298869056 (21.70 GB)
telemt_user_unique_ips_current{user="hello"} 57
```