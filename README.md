# Server Metrics 2026-03-11 11:11:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 74691.2 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1668433
telemt_connections_bad_total 25368
telemt_handshake_timeouts_total 43656
telemt_upstream_connect_attempt_total 15583
telemt_upstream_connect_success_total 15574
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 807
telemt_me_reconnect_attempts_total 23515
telemt_me_reconnect_success_total 11816
telemt_me_reader_eof_total 12753
telemt_me_idle_close_by_peer_total 12753
telemt_me_route_drop_no_conn_total 615141
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1516542
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7897
telemt_desync_full_logged_total 2140
telemt_desync_suppressed_total 5757
telemt_desync_frames_bucket_total{bucket="1_2"} 2026
telemt_desync_frames_bucket_total{bucket="3_10"} 3003
telemt_desync_frames_bucket_total{bucket="gt_10"} 2868
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12299
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11810
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 483
telemt_user_connections_total{user="hello"} 1515122
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 19712056852 (18.36 GB)
telemt_user_octets_to_client{user="hello"} 432271301840 (402.58 GB)
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74747.9 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635615
telemt_connections_bad_total 10825
telemt_handshake_timeouts_total 39469
telemt_upstream_connect_attempt_total 24566
telemt_upstream_connect_success_total 21633
telemt_upstream_connect_fail_total 2933
telemt_upstream_connect_attempts_per_request{bucket="1"} 24566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2933
telemt_me_keepalive_timeout_total 2183
telemt_me_reconnect_attempts_total 15798
telemt_me_reconnect_success_total 14951
telemt_me_reader_eof_total 15835
telemt_me_idle_close_by_peer_total 15833
telemt_me_route_drop_no_conn_total 258856
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538798
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2466
telemt_desync_full_logged_total 772
telemt_desync_suppressed_total 1694
telemt_desync_frames_bucket_total{bucket="1_2"} 802
telemt_desync_frames_bucket_total{bucket="3_10"} 889
telemt_desync_frames_bucket_total{bucket="gt_10"} 775
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 15138
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14929
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 541020
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 5583764462 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 151121785620 (140.74 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 74747.7 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1104257
telemt_connections_bad_total 7814
telemt_handshake_timeouts_total 105314
telemt_upstream_connect_attempt_total 20138
telemt_upstream_connect_success_total 19891
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 20138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 822
telemt_me_reconnect_attempts_total 28694
telemt_me_reconnect_success_total 15069
telemt_me_reader_eof_total 16178
telemt_me_idle_close_by_peer_total 16178
telemt_me_route_drop_no_conn_total 369812
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 950187
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2634
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1853
telemt_desync_frames_bucket_total{bucket="1_2"} 623
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 1025
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15686
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15058
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 950934
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 11087155109 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 288881076457 (269.04 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 74748.1 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800700
telemt_connections_bad_total 70250
telemt_handshake_timeouts_total 74913
telemt_upstream_connect_attempt_total 20304
telemt_upstream_connect_success_total 20304
telemt_upstream_connect_attempts_per_request{bucket="1"} 20304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 801
telemt_me_reconnect_attempts_total 17646
telemt_me_reconnect_success_total 16587
telemt_me_reader_eof_total 17610
telemt_me_idle_close_by_peer_total 17609
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 253760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632468
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1389
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 855
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 508
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 16785
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16562
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 631836
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 7295567188 (6.79 GB)
telemt_user_octets_to_client{user="hello"} 180546696952 (168.15 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 74747.8 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858792
telemt_connections_bad_total 6094
telemt_handshake_timeouts_total 8229
telemt_upstream_connect_attempt_total 20240
telemt_upstream_connect_success_total 20156
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 20240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 865
telemt_me_reconnect_attempts_total 20111
telemt_me_reconnect_success_total 16312
telemt_me_reader_eof_total 17212
telemt_me_idle_close_by_peer_total 17212
telemt_me_route_drop_no_conn_total 299910
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779238
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3245
telemt_desync_full_logged_total 1196
telemt_desync_suppressed_total 2049
telemt_desync_frames_bucket_total{bucket="1_2"} 1105
telemt_desync_frames_bucket_total{bucket="3_10"} 1289
telemt_desync_frames_bucket_total{bucket="gt_10"} 851
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16635
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 16312
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 779008
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 11748338671 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 283496455098 (264.03 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 126
```