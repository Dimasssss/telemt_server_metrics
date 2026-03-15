# Server Metrics 2026-03-15 13:24:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 54570.3 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1614382
telemt_connections_bad_total 94362
telemt_handshake_timeouts_total 14981
telemt_upstream_connect_attempt_total 10886
telemt_upstream_connect_success_total 10837
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12984
telemt_me_reconnect_success_total 8098
telemt_me_reader_eof_total 8686
telemt_me_idle_close_by_peer_total 8686
telemt_me_route_drop_no_conn_total 547201
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1359894
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5019
telemt_desync_full_logged_total 1418
telemt_desync_suppressed_total 3601
telemt_desync_frames_bucket_total{bucket="1_2"} 1284
telemt_desync_frames_bucket_total{bucket="3_10"} 1956
telemt_desync_frames_bucket_total{bucket="gt_10"} 1779
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8377
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8087
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 1359544
telemt_user_connections_current{user="hello"} 2378
telemt_user_octets_from_client{user="hello"} 18934002720 (17.63 GB)
telemt_user_octets_to_client{user="hello"} 543218840988 (505.91 GB)
telemt_user_unique_ips_current{user="hello"} 667
telemt_user_unique_ips_recent_window{user="hello"} 310
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 54571.1 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647818
telemt_connections_bad_total 33844
telemt_handshake_timeouts_total 45198
telemt_upstream_connect_attempt_total 14103
telemt_upstream_connect_success_total 14033
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6344
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11042
telemt_me_reconnect_success_total 10960
telemt_me_reader_eof_total 11576
telemt_me_idle_close_by_peer_total 11576
telemt_me_route_drop_no_conn_total 163374
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492820
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1929
telemt_desync_full_logged_total 666
telemt_desync_suppressed_total 1263
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11088
telemt_me_writer_restored_same_endpoint_total 10948
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 493088
telemt_user_connections_current{user="hello"} 826
telemt_user_octets_from_client{user="hello"} 6956714755 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 185908612976 (173.14 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 54571.1 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1341465
telemt_connections_bad_total 42287
telemt_handshake_timeouts_total 139128
telemt_upstream_connect_attempt_total 12126
telemt_upstream_connect_success_total 12070
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10564
telemt_me_reconnect_success_total 9315
telemt_me_reader_eof_total 9872
telemt_me_idle_close_by_peer_total 9872
telemt_me_route_drop_no_conn_total 384446
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 870241
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2230
telemt_desync_full_logged_total 813
telemt_desync_suppressed_total 1417
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 843
telemt_desync_frames_bucket_total{bucket="gt_10"} 883
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9475
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9296
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 866727
telemt_user_connections_current{user="hello"} 1290
telemt_user_octets_from_client{user="hello"} 12575285188 (11.71 GB)
telemt_user_octets_to_client{user="hello"} 318580393320 (296.70 GB)
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 54571.1 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656098
telemt_connections_bad_total 68899
telemt_handshake_timeouts_total 35777
telemt_upstream_connect_attempt_total 67396
telemt_upstream_connect_success_total 66971
telemt_upstream_connect_fail_total 425
telemt_upstream_connect_attempts_per_request{bucket="1"} 67396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 425
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 45350
telemt_me_reconnect_success_total 11767
telemt_me_reader_eof_total 13149
telemt_me_idle_close_by_peer_total 13149
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 167717
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438251
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1157
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12927
telemt_me_refill_failed_total 1050
telemt_me_writer_restored_same_endpoint_total 11735
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1160
telemt_user_connections_total{user="hello"} 490587
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 9260653512 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 169366990734 (157.74 GB)
telemt_user_msgs_from_client{user="hello"} 980794
telemt_user_msgs_to_client{user="hello"} 3451719
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 54572.1 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688765
telemt_connections_bad_total 8921
telemt_handshake_timeouts_total 13942
telemt_upstream_connect_attempt_total 12096
telemt_upstream_connect_success_total 12032
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 12965
telemt_me_reconnect_success_total 9297
telemt_me_reader_eof_total 9957
telemt_me_idle_close_by_peer_total 9957
telemt_me_route_drop_no_conn_total 172123
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558874
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2096
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1395
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9521
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9289
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 558915
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 7119995132 (6.63 GB)
telemt_user_octets_to_client{user="hello"} 207753842112 (193.49 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 118
```