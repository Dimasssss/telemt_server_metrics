# Server Metrics 2026-03-11 02:58:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 45075.6 (12h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 871358
telemt_connections_bad_total 10063
telemt_handshake_timeouts_total 17643
telemt_upstream_connect_attempt_total 9772
telemt_upstream_connect_success_total 9763
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 9772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 510
telemt_me_reconnect_attempts_total 19118
telemt_me_reconnect_success_total 7447
telemt_me_reader_eof_total 8132
telemt_me_idle_close_by_peer_total 8132
telemt_me_route_drop_no_conn_total 345906
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813841
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3777
telemt_desync_full_logged_total 1049
telemt_desync_suppressed_total 2728
telemt_desync_frames_bucket_total{bucket="1_2"} 1092
telemt_desync_frames_bucket_total{bucket="3_10"} 1423
telemt_desync_frames_bucket_total{bucket="gt_10"} 1262
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7877
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 7441
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 813575
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 10993013268 (10.24 GB)
telemt_user_octets_to_client{user="hello"} 242138135388 (225.51 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 45132.4 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364865
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 18324
telemt_upstream_connect_attempt_total 17663
telemt_upstream_connect_success_total 14771
telemt_upstream_connect_fail_total 2891
telemt_upstream_connect_attempts_per_request{bucket="1"} 17662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2891
telemt_me_keepalive_timeout_total 1753
telemt_me_reconnect_attempts_total 10341
telemt_me_reconnect_success_total 9523
telemt_me_reader_eof_total 10048
telemt_me_idle_close_by_peer_total 10046
telemt_me_route_drop_no_conn_total 178368
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312795
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 638
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 9641
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 9502
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 315065
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 2969834970 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 73665542024 (68.61 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 45132.1 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609963
telemt_connections_bad_total 4922
telemt_handshake_timeouts_total 34709
telemt_upstream_connect_attempt_total 12290
telemt_upstream_connect_success_total 12127
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 19819
telemt_me_reconnect_success_total 8751
telemt_me_reader_eof_total 9505
telemt_me_idle_close_by_peer_total 9505
telemt_me_route_drop_no_conn_total 207183
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541481
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1572
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 1108
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 549
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 9215
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 8740
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 542376
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 7047239553 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 166177818333 (154.77 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 45132.5 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 458764
telemt_connections_bad_total 42658
telemt_handshake_timeouts_total 44616
telemt_upstream_connect_attempt_total 13133
telemt_upstream_connect_success_total 13133
telemt_upstream_connect_attempts_per_request{bucket="1"} 13133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 459
telemt_me_reconnect_attempts_total 11872
telemt_me_reconnect_success_total 10834
telemt_me_reader_eof_total 11493
telemt_me_idle_close_by_peer_total 11493
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 137103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357827
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 462
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 10964
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10815
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 357496
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 4365155004 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 95636683776 (89.07 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 45132.2 (12h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483837
telemt_connections_bad_total 5800
telemt_handshake_timeouts_total 3051
telemt_upstream_connect_attempt_total 13277
telemt_upstream_connect_success_total 13220
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 532
telemt_me_reconnect_attempts_total 14658
telemt_me_reconnect_success_total 10881
telemt_me_reader_eof_total 11476
telemt_me_idle_close_by_peer_total 11476
telemt_me_route_drop_no_conn_total 156076
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 440942
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2317
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1413
telemt_desync_frames_bucket_total{bucket="1_2"} 859
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 474
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 11140
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 10881
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 440604
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 8553954272 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 159463383944 (148.51 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 43
```