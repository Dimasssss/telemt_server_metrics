# Server Metrics 2026-03-11 21:19:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 111141.2 (30h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2808726
telemt_connections_bad_total 65194
telemt_handshake_timeouts_total 62603
telemt_upstream_connect_attempt_total 23736
telemt_upstream_connect_success_total 23724
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5441
telemt_me_reconnect_attempts_total 35988
telemt_me_reconnect_success_total 18090
telemt_me_reader_eof_total 19521
telemt_me_idle_close_by_peer_total 19521
telemt_me_route_drop_no_conn_total 1053116
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2546368
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12732
telemt_desync_full_logged_total 3538
telemt_desync_suppressed_total 9194
telemt_desync_frames_bucket_total{bucket="1_2"} 3145
telemt_desync_frames_bucket_total{bucket="3_10"} 4886
telemt_desync_frames_bucket_total{bucket="gt_10"} 4701
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 18858
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 18084
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 768
telemt_user_connections_total{user="hello"} 2544701
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 38697917280 (36.04 GB)
telemt_user_octets_to_client{user="hello"} 735561879832 (685.05 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 111197.8 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1023590
telemt_connections_bad_total 17056
telemt_handshake_timeouts_total 90473
telemt_upstream_connect_attempt_total 33838
telemt_upstream_connect_success_total 30859
telemt_upstream_connect_fail_total 2979
telemt_upstream_connect_attempts_per_request{bucket="1"} 33838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2979
telemt_me_keepalive_timeout_total 2914
telemt_me_reconnect_attempts_total 24445
telemt_me_reconnect_success_total 22315
telemt_me_reader_eof_total 23648
telemt_me_idle_close_by_peer_total 23645
telemt_me_route_drop_no_conn_total 387254
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 856294
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3383
telemt_desync_full_logged_total 1102
telemt_desync_suppressed_total 2281
telemt_desync_frames_bucket_total{bucket="1_2"} 1106
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 22643
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 22292
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 858730
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 10370941322 (9.66 GB)
telemt_user_octets_to_client{user="hello"} 259066951848 (241.27 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 111197.6 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1788280
telemt_connections_bad_total 11436
telemt_handshake_timeouts_total 137229
telemt_upstream_connect_attempt_total 40143
telemt_upstream_connect_success_total 39783
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 40142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13041
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_keepalive_timeout_total 2059
telemt_me_reconnect_attempts_total 62563
telemt_me_reconnect_success_total 20679
telemt_me_reader_eof_total 22847
telemt_me_idle_close_by_peer_total 22847
telemt_me_route_drop_no_conn_total 646025
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1560723
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4213
telemt_desync_full_logged_total 1243
telemt_desync_suppressed_total 2970
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 1602
telemt_desync_frames_bucket_total{bucket="gt_10"} 1625
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22270
telemt_me_refill_failed_total 1303
telemt_me_writer_restored_same_endpoint_total 20667
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1591
telemt_user_connections_total{user="hello"} 1572743
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 20012841124 (18.64 GB)
telemt_user_octets_to_client{user="hello"} 480713653162 (447.70 GB)
telemt_user_msgs_from_client{user="hello"} 162703
telemt_user_msgs_to_client{user="hello"} 969883
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 111198.1 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1279832
telemt_connections_bad_total 78279
telemt_handshake_timeouts_total 111801
telemt_upstream_connect_attempt_total 29835
telemt_upstream_connect_success_total 29835
telemt_upstream_connect_attempts_per_request{bucket="1"} 29835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1554
telemt_me_reconnect_attempts_total 28890
telemt_me_reconnect_success_total 24270
telemt_me_reader_eof_total 25778
telemt_me_idle_close_by_peer_total 25777
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 429556
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1053773
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2212
telemt_desync_full_logged_total 832
telemt_desync_suppressed_total 1380
telemt_desync_frames_bucket_total{bucket="1_2"} 781
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24674
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 24237
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 1052893
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 12336264740 (11.49 GB)
telemt_user_octets_to_client{user="hello"} 318398988752 (296.53 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15874.0 (4h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216392
telemt_connections_bad_total 5176
telemt_handshake_timeouts_total 2443
telemt_upstream_connect_attempt_total 4560
telemt_upstream_connect_success_total 4559
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 3738
telemt_me_reconnect_success_total 3704
telemt_me_reader_eof_total 3843
telemt_me_idle_close_by_peer_total 3843
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 73234
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191650
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 480
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3747
telemt_me_writer_restored_same_endpoint_total 3677
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 191612
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 9688327096 (9.02 GB)
telemt_user_octets_to_client{user="hello"} 66451360740 (61.89 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 42
```