# Server Metrics 2026-03-11 00:20:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 35628.7 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782975
telemt_connections_bad_total 9521
telemt_handshake_timeouts_total 8973
telemt_upstream_connect_attempt_total 7742
telemt_upstream_connect_success_total 7733
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 17546
telemt_me_reconnect_success_total 5882
telemt_me_reader_eof_total 6455
telemt_me_idle_close_by_peer_total 6455
telemt_me_route_drop_no_conn_total 322616
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 740912
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3554
telemt_desync_full_logged_total 993
telemt_desync_suppressed_total 2561
telemt_desync_frames_bucket_total{bucket="1_2"} 1033
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1202
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6295
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5876
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 740697
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 10205102220 (9.50 GB)
telemt_user_octets_to_client{user="hello"} 221237985468 (206.04 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 35685.5 (9h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337956
telemt_connections_bad_total 2384
telemt_handshake_timeouts_total 17629
telemt_upstream_connect_attempt_total 14716
telemt_upstream_connect_success_total 11838
telemt_upstream_connect_fail_total 2878
telemt_upstream_connect_attempts_per_request{bucket="1"} 14716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2878
telemt_me_keepalive_timeout_total 1705
telemt_me_reconnect_attempts_total 7885
telemt_me_reconnect_success_total 7072
telemt_me_reader_eof_total 7457
telemt_me_idle_close_by_peer_total 7455
telemt_me_route_drop_no_conn_total 171607
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287460
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1740
telemt_desync_full_logged_total 486
telemt_desync_suppressed_total 1254
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7170
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 7051
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 289729
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2796401742 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 69719452052 (64.93 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 35685.2 (9h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561823
telemt_connections_bad_total 3862
telemt_handshake_timeouts_total 34042
telemt_upstream_connect_attempt_total 9787
telemt_upstream_connect_success_total 9652
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 9787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 506
telemt_me_reconnect_attempts_total 17819
telemt_me_reconnect_success_total 6760
telemt_me_reader_eof_total 7383
telemt_me_idle_close_by_peer_total 7383
telemt_me_route_drop_no_conn_total 193444
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495421
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1521
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 7201
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6749
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 441
telemt_user_connections_total{user="hello"} 496346
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 6794325001 (6.33 GB)
telemt_user_octets_to_client{user="hello"} 153125381425 (142.61 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 35685.8 (9h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408223
telemt_connections_bad_total 34022
telemt_handshake_timeouts_total 37919
telemt_upstream_connect_attempt_total 10101
telemt_upstream_connect_success_total 10101
telemt_upstream_connect_attempts_per_request{bucket="1"} 10101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 399
telemt_me_reconnect_attempts_total 9313
telemt_me_reconnect_success_total 8282
telemt_me_reader_eof_total 8740
telemt_me_idle_close_by_peer_total 8740
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 126796
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323297
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8396
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8266
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 322972
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 4172661844 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 90127713564 (83.94 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 35685.3 (9h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 432464
telemt_connections_bad_total 4007
telemt_handshake_timeouts_total 2738
telemt_upstream_connect_attempt_total 10824
telemt_upstream_connect_success_total 10781
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 10824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 501
telemt_me_reconnect_attempts_total 12694
telemt_me_reconnect_success_total 8928
telemt_me_reader_eof_total 9386
telemt_me_idle_close_by_peer_total 9386
telemt_me_route_drop_no_conn_total 145505
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399252
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2257
telemt_desync_full_logged_total 870
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 9163
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8928
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 399000
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 8309169232 (7.74 GB)
telemt_user_octets_to_client{user="hello"} 145458994908 (135.47 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 32
```