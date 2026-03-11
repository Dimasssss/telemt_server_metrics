# Server Metrics 2026-03-11 12:38:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 79897.6 (22h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1851592
telemt_connections_bad_total 27358
telemt_handshake_timeouts_total 47729
telemt_upstream_connect_attempt_total 16540
telemt_upstream_connect_success_total 16531
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 861
telemt_me_reconnect_attempts_total 25329
telemt_me_reconnect_success_total 12501
telemt_me_reader_eof_total 13525
telemt_me_idle_close_by_peer_total 13525
telemt_me_route_drop_no_conn_total 680976
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1688484
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8837
telemt_desync_full_logged_total 2383
telemt_desync_suppressed_total 6454
telemt_desync_frames_bucket_total{bucket="1_2"} 2196
telemt_desync_frames_bucket_total{bucket="3_10"} 3394
telemt_desync_frames_bucket_total{bucket="gt_10"} 3247
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13037
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12495
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 1687026
telemt_user_connections_current{user="hello"} 1486
telemt_user_octets_from_client{user="hello"} 22296826244 (20.77 GB)
telemt_user_octets_to_client{user="hello"} 478640407300 (445.77 GB)
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79954.3 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703894
telemt_connections_bad_total 13019
telemt_handshake_timeouts_total 49614
telemt_upstream_connect_attempt_total 25971
telemt_upstream_connect_success_total 23030
telemt_upstream_connect_fail_total 2941
telemt_upstream_connect_attempts_per_request{bucket="1"} 25971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2941
telemt_me_keepalive_timeout_total 2430
telemt_me_reconnect_attempts_total 16944
telemt_me_reconnect_success_total 16085
telemt_me_reader_eof_total 17020
telemt_me_idle_close_by_peer_total 17017
telemt_me_route_drop_no_conn_total 277594
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 591866
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2657
telemt_desync_full_logged_total 838
telemt_desync_suppressed_total 1819
telemt_desync_frames_bucket_total{bucket="1_2"} 843
telemt_desync_frames_bucket_total{bucket="3_10"} 972
telemt_desync_frames_bucket_total{bucket="gt_10"} 842
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16292
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16062
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 594106
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 6372711314 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 170205233848 (158.52 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 79954.1 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1213922
telemt_connections_bad_total 8001
telemt_handshake_timeouts_total 114494
telemt_upstream_connect_attempt_total 21436
telemt_upstream_connect_success_total 21177
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 21436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 872
telemt_me_reconnect_attempts_total 29727
telemt_me_reconnect_success_total 16092
telemt_me_reader_eof_total 17256
telemt_me_idle_close_by_peer_total 17256
telemt_me_route_drop_no_conn_total 412368
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1045161
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2834
telemt_desync_full_logged_total 843
telemt_desync_suppressed_total 1991
telemt_desync_frames_bucket_total{bucket="1_2"} 689
telemt_desync_frames_bucket_total{bucket="3_10"} 1067
telemt_desync_frames_bucket_total{bucket="gt_10"} 1078
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16730
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 16081
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 1045818
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 12206070349 (11.37 GB)
telemt_user_octets_to_client{user="hello"} 314185973525 (292.61 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 79954.5 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875146
telemt_connections_bad_total 75015
telemt_handshake_timeouts_total 80118
telemt_upstream_connect_attempt_total 21741
telemt_upstream_connect_success_total 21741
telemt_upstream_connect_attempts_per_request{bucket="1"} 21741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 869
telemt_me_reconnect_attempts_total 18824
telemt_me_reconnect_success_total 17759
telemt_me_reader_eof_total 18842
telemt_me_idle_close_by_peer_total 18841
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 280428
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 695553
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1461
telemt_desync_full_logged_total 568
telemt_desync_suppressed_total 893
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 527
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17974
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17732
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 694916
telemt_user_connections_current{user="hello"} 568
telemt_user_octets_from_client{user="hello"} 7865481168 (7.33 GB)
telemt_user_octets_to_client{user="hello"} 198839836152 (185.18 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79954.3 (22h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946882
telemt_connections_bad_total 6280
telemt_handshake_timeouts_total 8883
telemt_upstream_connect_attempt_total 21862
telemt_upstream_connect_success_total 21767
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 21862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 930
telemt_me_reconnect_attempts_total 21726
telemt_me_reconnect_success_total 17662
telemt_me_reader_eof_total 18633
telemt_me_idle_close_by_peer_total 18633
telemt_me_route_drop_no_conn_total 332983
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 859908
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3506
telemt_desync_full_logged_total 1296
telemt_desync_suppressed_total 2210
telemt_desync_frames_bucket_total{bucket="1_2"} 1200
telemt_desync_frames_bucket_total{bucket="3_10"} 1356
telemt_desync_frames_bucket_total{bucket="gt_10"} 950
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18015
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17662
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 859663
telemt_user_connections_current{user="hello"} 766
telemt_user_octets_from_client{user="hello"} 12752689339 (11.88 GB)
telemt_user_octets_to_client{user="hello"} 310257410494 (288.95 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 96
```