# Server Metrics 2026-03-11 10:46:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 73159.8 (20h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1617065
telemt_connections_bad_total 24745
telemt_handshake_timeouts_total 42136
telemt_upstream_connect_attempt_total 15154
telemt_upstream_connect_success_total 15145
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 801
telemt_me_reconnect_attempts_total 23131
telemt_me_reconnect_success_total 11438
telemt_me_reader_eof_total 12371
telemt_me_idle_close_by_peer_total 12371
telemt_me_route_drop_no_conn_total 596119
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1469306
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7440
telemt_desync_full_logged_total 2036
telemt_desync_suppressed_total 5404
telemt_desync_frames_bucket_total{bucket="1_2"} 1940
telemt_desync_frames_bucket_total{bucket="3_10"} 2818
telemt_desync_frames_bucket_total{bucket="gt_10"} 2682
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11916
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11432
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 1467885
telemt_user_connections_current{user="hello"} 1223
telemt_user_octets_from_client{user="hello"} 19009112880 (17.70 GB)
telemt_user_octets_to_client{user="hello"} 419276701064 (390.48 GB)
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73216.6 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618533
telemt_connections_bad_total 10279
telemt_handshake_timeouts_total 38742
telemt_upstream_connect_attempt_total 24255
telemt_upstream_connect_success_total 21322
telemt_upstream_connect_fail_total 2933
telemt_upstream_connect_attempts_per_request{bucket="1"} 24255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2933
telemt_me_keepalive_timeout_total 2157
telemt_me_reconnect_attempts_total 15544
telemt_me_reconnect_success_total 14699
telemt_me_reader_eof_total 15565
telemt_me_idle_close_by_peer_total 15563
telemt_me_route_drop_no_conn_total 252618
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 523458
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2381
telemt_desync_full_logged_total 742
telemt_desync_suppressed_total 1639
telemt_desync_frames_bucket_total{bucket="1_2"} 784
telemt_desync_frames_bucket_total{bucket="3_10"} 856
telemt_desync_frames_bucket_total{bucket="gt_10"} 741
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 14879
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14677
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 525684
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 5275449762 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 146666342836 (136.59 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 73216.5 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070942
telemt_connections_bad_total 7707
telemt_handshake_timeouts_total 103640
telemt_upstream_connect_attempt_total 19764
telemt_upstream_connect_success_total 19520
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 810
telemt_me_reconnect_attempts_total 28383
telemt_me_reconnect_success_total 14762
telemt_me_reader_eof_total 15868
telemt_me_idle_close_by_peer_total 15868
telemt_me_route_drop_no_conn_total 354999
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 919017
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2570
telemt_desync_full_logged_total 762
telemt_desync_suppressed_total 1808
telemt_desync_frames_bucket_total{bucket="1_2"} 612
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 1002
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15376
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14751
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 919845
telemt_user_connections_current{user="hello"} 747
telemt_user_octets_from_client{user="hello"} 10764800329 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 280469990201 (261.21 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 73216.9 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779657
telemt_connections_bad_total 68852
telemt_handshake_timeouts_total 73901
telemt_upstream_connect_attempt_total 20015
telemt_upstream_connect_success_total 20015
telemt_upstream_connect_attempts_per_request{bucket="1"} 20015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 772
telemt_me_reconnect_attempts_total 17409
telemt_me_reconnect_success_total 16350
telemt_me_reader_eof_total 17356
telemt_me_idle_close_by_peer_total 17355
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 245915
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614151
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1363
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 841
telemt_desync_frames_bucket_total{bucket="1_2"} 475
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 385
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16544
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16325
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 613521
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 7075226208 (6.59 GB)
telemt_user_octets_to_client{user="hello"} 175701102580 (163.63 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73216.7 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 833059
telemt_connections_bad_total 6086
telemt_handshake_timeouts_total 7881
telemt_upstream_connect_attempt_total 19715
telemt_upstream_connect_success_total 19632
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 19715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 818
telemt_me_reconnect_attempts_total 19646
telemt_me_reconnect_success_total 15849
telemt_me_reader_eof_total 16743
telemt_me_idle_close_by_peer_total 16743
telemt_me_route_drop_no_conn_total 289688
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 755804
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3143
telemt_desync_full_logged_total 1172
telemt_desync_suppressed_total 1971
telemt_desync_frames_bucket_total{bucket="1_2"} 1080
telemt_desync_frames_bucket_total{bucket="3_10"} 1262
telemt_desync_frames_bucket_total{bucket="gt_10"} 801
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16165
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15849
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 755544
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 11474633035 (10.69 GB)
telemt_user_octets_to_client{user="hello"} 276619285038 (257.62 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 103
```