# Server Metrics 2026-03-11 08:13:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 63984.4 (17h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1310497
telemt_connections_bad_total 14208
telemt_handshake_timeouts_total 39792
telemt_upstream_connect_attempt_total 13248
telemt_upstream_connect_success_total 13239
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 13248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 749
telemt_me_reconnect_attempts_total 21684
telemt_me_reconnect_success_total 9999
telemt_me_reader_eof_total 10857
telemt_me_idle_close_by_peer_total 10857
telemt_me_route_drop_no_conn_total 483148
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1187114
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5865
telemt_desync_full_logged_total 1632
telemt_desync_suppressed_total 4233
telemt_desync_frames_bucket_total{bucket="1_2"} 1533
telemt_desync_frames_bucket_total{bucket="3_10"} 2234
telemt_desync_frames_bucket_total{bucket="gt_10"} 2098
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10463
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9993
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 1186764
telemt_user_connections_current{user="hello"} 1235
telemt_user_octets_from_client{user="hello"} 15759607780 (14.68 GB)
telemt_user_octets_to_client{user="hello"} 346406583616 (322.62 GB)
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 64041.3 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508309
telemt_connections_bad_total 7547
telemt_handshake_timeouts_total 28729
telemt_upstream_connect_attempt_total 22221
telemt_upstream_connect_success_total 19300
telemt_upstream_connect_fail_total 2921
telemt_upstream_connect_attempts_per_request{bucket="1"} 22221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8334
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2921
telemt_me_keepalive_timeout_total 2057
telemt_me_reconnect_attempts_total 13956
telemt_me_reconnect_success_total 13126
telemt_me_reader_eof_total 13888
telemt_me_idle_close_by_peer_total 13886
telemt_me_route_drop_no_conn_total 217778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431738
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2124
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1474
telemt_desync_frames_bucket_total{bucket="1_2"} 697
telemt_desync_frames_bucket_total{bucket="3_10"} 769
telemt_desync_frames_bucket_total{bucket="gt_10"} 658
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13278
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 13104
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 433980
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 4228327218 (3.94 GB)
telemt_user_octets_to_client{user="hello"} 116183951272 (108.20 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 64041.0 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857784
telemt_connections_bad_total 7165
telemt_handshake_timeouts_total 51097
telemt_upstream_connect_attempt_total 17420
telemt_upstream_connect_success_total 17206
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 17420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 748
telemt_me_reconnect_attempts_total 25262
telemt_me_reconnect_success_total 12904
telemt_me_reader_eof_total 13876
telemt_me_idle_close_by_peer_total 13876
telemt_me_route_drop_no_conn_total 290423
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763189
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2201
telemt_desync_full_logged_total 650
telemt_desync_suppressed_total 1551
telemt_desync_frames_bucket_total{bucket="1_2"} 515
telemt_desync_frames_bucket_total{bucket="3_10"} 800
telemt_desync_frames_bucket_total{bucket="gt_10"} 886
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 13452
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12893
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 548
telemt_user_connections_total{user="hello"} 763966
telemt_user_connections_current{user="hello"} 634
telemt_user_octets_from_client{user="hello"} 9086907025 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 231294967941 (215.41 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 64041.4 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 650324
telemt_connections_bad_total 59927
telemt_handshake_timeouts_total 63666
telemt_upstream_connect_attempt_total 17841
telemt_upstream_connect_success_total 17841
telemt_upstream_connect_attempts_per_request{bucket="1"} 17841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 682
telemt_me_reconnect_attempts_total 15671
telemt_me_reconnect_success_total 14619
telemt_me_reader_eof_total 15533
telemt_me_idle_close_by_peer_total 15532
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 201463
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505801
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1221
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 762
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 14791
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14597
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 505178
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 5992726100 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 139553469104 (129.97 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 64041.1 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682818
telemt_connections_bad_total 5976
telemt_handshake_timeouts_total 6195
telemt_upstream_connect_attempt_total 17737
telemt_upstream_connect_success_total 17665
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 17737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 718
telemt_me_reconnect_attempts_total 18116
telemt_me_reconnect_success_total 14328
telemt_me_reader_eof_total 15141
telemt_me_idle_close_by_peer_total 15141
telemt_me_route_drop_no_conn_total 230045
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622340
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2812
telemt_desync_full_logged_total 1060
telemt_desync_suppressed_total 1752
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14627
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 14328
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 622035
telemt_user_connections_current{user="hello"} 715
telemt_user_octets_from_client{user="hello"} 10241611343 (9.54 GB)
telemt_user_octets_to_client{user="hello"} 226700570270 (211.13 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 100
```