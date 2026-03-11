# Server Metrics 2026-03-11 17:34:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 97669.8 (27h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2462361
telemt_connections_bad_total 46087
telemt_handshake_timeouts_total 54765
telemt_upstream_connect_attempt_total 20524
telemt_upstream_connect_success_total 20512
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10060
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5210
telemt_me_reconnect_attempts_total 33443
telemt_me_reconnect_success_total 15566
telemt_me_reader_eof_total 16864
telemt_me_idle_close_by_peer_total 16864
telemt_me_route_drop_no_conn_total 916681
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2252183
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11558
telemt_desync_full_logged_total 3179
telemt_desync_suppressed_total 8379
telemt_desync_frames_bucket_total{bucket="1_2"} 2850
telemt_desync_frames_bucket_total{bucket="3_10"} 4466
telemt_desync_frames_bucket_total{bucket="gt_10"} 4242
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16298
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15560
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 2250626
telemt_user_connections_current{user="hello"} 1242
telemt_user_octets_from_client{user="hello"} 30740526500 (28.63 GB)
telemt_user_octets_to_client{user="hello"} 635517493912 (591.87 GB)
telemt_user_unique_ips_current{user="hello"} 347
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 97726.4 (27h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924390
telemt_connections_bad_total 16330
telemt_handshake_timeouts_total 78734
telemt_upstream_connect_attempt_total 30729
telemt_upstream_connect_success_total 27767
telemt_upstream_connect_fail_total 2962
telemt_upstream_connect_attempts_per_request{bucket="1"} 30729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2962
telemt_me_keepalive_timeout_total 2757
telemt_me_reconnect_attempts_total 22007
telemt_me_reconnect_success_total 19901
telemt_me_reader_eof_total 21058
telemt_me_idle_close_by_peer_total 21055
telemt_me_route_drop_no_conn_total 351078
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772673
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3054
telemt_desync_full_logged_total 973
telemt_desync_suppressed_total 2081
telemt_desync_frames_bucket_total{bucket="1_2"} 927
telemt_desync_frames_bucket_total{bucket="3_10"} 1097
telemt_desync_frames_bucket_total{bucket="gt_10"} 1030
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 20177
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19878
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 775134
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 9303028654 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 219453596536 (204.38 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 97726.4 (27h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1579457
telemt_connections_bad_total 9538
telemt_handshake_timeouts_total 127386
telemt_upstream_connect_attempt_total 25359
telemt_upstream_connect_success_total 25038
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 25359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1889
telemt_me_reconnect_attempts_total 45027
telemt_me_reconnect_success_total 19024
telemt_me_reader_eof_total 20663
telemt_me_idle_close_by_peer_total 20663
telemt_me_route_drop_no_conn_total 576184
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1381631
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3701
telemt_desync_full_logged_total 1079
telemt_desync_suppressed_total 2622
telemt_desync_frames_bucket_total{bucket="1_2"} 898
telemt_desync_frames_bucket_total{bucket="3_10"} 1411
telemt_desync_frames_bucket_total{bucket="gt_10"} 1392
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 20098
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19012
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1074
telemt_user_connections_total{user="hello"} 1381320
telemt_user_connections_current{user="hello"} 892
telemt_user_octets_from_client{user="hello"} 17108377289 (15.93 GB)
telemt_user_octets_to_client{user="hello"} 419648364645 (390.83 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 97726.8 (27h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1131097
telemt_connections_bad_total 77988
telemt_handshake_timeouts_total 107000
telemt_upstream_connect_attempt_total 26389
telemt_upstream_connect_success_total 26389
telemt_upstream_connect_attempts_per_request{bucket="1"} 26389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1255
telemt_me_reconnect_attempts_total 23640
telemt_me_reconnect_success_total 21500
telemt_me_reader_eof_total 22783
telemt_me_idle_close_by_peer_total 22782
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 373946
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 912539
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1918
telemt_desync_full_logged_total 733
telemt_desync_suppressed_total 1185
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 562
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21795
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 21468
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 911816
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 10975502616 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 277933554220 (258.85 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2403.1 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44693
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 678
telemt_upstream_connect_success_total 678
telemt_upstream_connect_attempts_per_request{bucket="1"} 678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 520
telemt_me_reconnect_success_total 516
telemt_me_reader_eof_total 481
telemt_me_idle_close_by_peer_total 481
telemt_me_route_drop_no_conn_total 13754
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41862
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 101
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_me_writer_removed_unexpected_total 504
telemt_me_writer_restored_same_endpoint_total 494
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 41862
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 5742975568 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 13514322348 (12.59 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 111
```