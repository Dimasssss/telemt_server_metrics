# Server Metrics 2026-03-11 16:28:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 93688.7 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2335525
telemt_connections_bad_total 40546
telemt_handshake_timeouts_total 53910
telemt_upstream_connect_attempt_total 19590
telemt_upstream_connect_success_total 19578
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 19590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5016
telemt_me_reconnect_attempts_total 32698
telemt_me_reconnect_success_total 14824
telemt_me_reader_eof_total 16077
telemt_me_idle_close_by_peer_total 16077
telemt_me_route_drop_no_conn_total 866756
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2136372
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11114
telemt_desync_full_logged_total 3031
telemt_desync_suppressed_total 8083
telemt_desync_frames_bucket_total{bucket="1_2"} 2752
telemt_desync_frames_bucket_total{bucket="3_10"} 4288
telemt_desync_frames_bucket_total{bucket="gt_10"} 4074
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 15546
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14818
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 722
telemt_user_connections_total{user="hello"} 2134830
telemt_user_connections_current{user="hello"} 1304
telemt_user_octets_from_client{user="hello"} 28828306036 (26.85 GB)
telemt_user_octets_to_client{user="hello"} 602821621972 (561.42 GB)
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93745.4 (26h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872842
telemt_connections_bad_total 15079
telemt_handshake_timeouts_total 68299
telemt_upstream_connect_attempt_total 29517
telemt_upstream_connect_success_total 26557
telemt_upstream_connect_fail_total 2960
telemt_upstream_connect_attempts_per_request{bucket="1"} 29517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2960
telemt_me_keepalive_timeout_total 2645
telemt_me_reconnect_attempts_total 20976
telemt_me_reconnect_success_total 18877
telemt_me_reader_eof_total 19986
telemt_me_idle_close_by_peer_total 19983
telemt_me_route_drop_no_conn_total 336440
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734263
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2957
telemt_desync_full_logged_total 943
telemt_desync_suppressed_total 2014
telemt_desync_frames_bucket_total{bucket="1_2"} 909
telemt_desync_frames_bucket_total{bucket="3_10"} 1060
telemt_desync_frames_bucket_total{bucket="gt_10"} 988
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19149
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18854
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 736723
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 8405074218 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 208044143008 (193.76 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 93745.3 (26h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1495759
telemt_connections_bad_total 8911
telemt_handshake_timeouts_total 125530
telemt_upstream_connect_attempt_total 24252
telemt_upstream_connect_success_total 23944
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 24252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_keepalive_timeout_total 1724
telemt_me_reconnect_attempts_total 41874
telemt_me_reconnect_success_total 18120
telemt_me_reader_eof_total 19669
telemt_me_idle_close_by_peer_total 19669
telemt_me_route_drop_no_conn_total 546892
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1307030
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3437
telemt_desync_full_logged_total 1017
telemt_desync_suppressed_total 2420
telemt_desync_frames_bucket_total{bucket="1_2"} 853
telemt_desync_frames_bucket_total{bucket="3_10"} 1299
telemt_desync_frames_bucket_total{bucket="gt_10"} 1285
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 19108
telemt_me_refill_failed_total 737
telemt_me_writer_restored_same_endpoint_total 18108
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 988
telemt_user_connections_total{user="hello"} 1306736
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 15832050769 (14.74 GB)
telemt_user_octets_to_client{user="hello"} 396386500633 (369.16 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 93745.6 (26h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1079043
telemt_connections_bad_total 77973
telemt_handshake_timeouts_total 104035
telemt_upstream_connect_attempt_total 25190
telemt_upstream_connect_success_total 25189
telemt_upstream_connect_attempts_per_request{bucket="1"} 25189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1104
telemt_me_reconnect_attempts_total 21568
telemt_me_reconnect_success_total 20490
telemt_me_reader_eof_total 21709
telemt_me_idle_close_by_peer_total 21708
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 353782
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 864157
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1788
telemt_desync_full_logged_total 691
telemt_desync_suppressed_total 1097
telemt_desync_frames_bucket_total{bucket="1_2"} 650
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 514
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20738
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 20459
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 863473
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 10366099532 (9.65 GB)
telemt_user_octets_to_client{user="hello"} 254812929200 (237.31 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93745.4 (26h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188686
telemt_connections_bad_total 6957
telemt_handshake_timeouts_total 11807
telemt_upstream_connect_attempt_total 25550
telemt_upstream_connect_success_total 25436
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 25550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2114
telemt_me_reconnect_attempts_total 24686
telemt_me_reconnect_success_total 20590
telemt_me_reader_eof_total 21701
telemt_me_idle_close_by_peer_total 21701
telemt_me_route_drop_no_conn_total 424419
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1082542
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4229
telemt_desync_full_logged_total 1509
telemt_desync_suppressed_total 2720
telemt_desync_frames_bucket_total{bucket="1_2"} 1399
telemt_desync_frames_bucket_total{bucket="3_10"} 1578
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20987
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 20590
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 1082242
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 20341053131 (18.94 GB)
telemt_user_octets_to_client{user="hello"} 375749668798 (349.94 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 107
```