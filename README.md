# Server Metrics 2026-03-15 16:07:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 64381.3 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2134627
telemt_connections_bad_total 121737
telemt_handshake_timeouts_total 25859
telemt_upstream_connect_attempt_total 12794
telemt_upstream_connect_success_total 12738
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14399
telemt_me_reconnect_success_total 9504
telemt_me_reader_eof_total 10160
telemt_me_idle_close_by_peer_total 10160
telemt_me_route_drop_no_conn_total 734458
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1799279
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6908
telemt_desync_full_logged_total 1902
telemt_desync_suppressed_total 5006
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 2646
telemt_desync_frames_bucket_total{bucket="gt_10"} 2560
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9814
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9493
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 1798784
telemt_user_connections_current{user="hello"} 2463
telemt_user_octets_from_client{user="hello"} 26449516164 (24.63 GB)
telemt_user_octets_to_client{user="hello"} 690212455708 (642.81 GB)
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 345
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 64382.1 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842189
telemt_connections_bad_total 44871
telemt_handshake_timeouts_total 59880
telemt_upstream_connect_attempt_total 16184
telemt_upstream_connect_success_total 16107
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 16184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12630
telemt_me_reconnect_success_total 12528
telemt_me_reader_eof_total 13232
telemt_me_idle_close_by_peer_total 13232
telemt_me_route_drop_no_conn_total 213909
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 643274
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2080
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 763
telemt_desync_frames_bucket_total{bucket="gt_10"} 552
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12689
telemt_me_writer_restored_same_endpoint_total 12516
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 643516
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 8946417127 (8.33 GB)
telemt_user_octets_to_client{user="hello"} 244136929320 (227.37 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 64382.0 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1917375
telemt_connections_bad_total 48138
telemt_handshake_timeouts_total 188708
telemt_upstream_connect_attempt_total 13992
telemt_upstream_connect_success_total 13926
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 13992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11931
telemt_me_reconnect_success_total 10666
telemt_me_reader_eof_total 11305
telemt_me_idle_close_by_peer_total 11305
telemt_me_route_drop_no_conn_total 492489
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1144705
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2799
telemt_desync_full_logged_total 1025
telemt_desync_suppressed_total 1774
telemt_desync_frames_bucket_total{bucket="1_2"} 652
telemt_desync_frames_bucket_total{bucket="3_10"} 1081
telemt_desync_frames_bucket_total{bucket="gt_10"} 1066
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10854
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10647
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 1140666
telemt_user_connections_current{user="hello"} 1385
telemt_user_octets_from_client{user="hello"} 16460087804 (15.33 GB)
telemt_user_octets_to_client{user="hello"} 407410345692 (379.43 GB)
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 64381.9 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 895096
telemt_connections_bad_total 77827
telemt_handshake_timeouts_total 43630
telemt_upstream_connect_attempt_total 168544
telemt_upstream_connect_success_total 168022
telemt_upstream_connect_fail_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 168543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 521
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 53167
telemt_me_reconnect_success_total 12720
telemt_me_reader_eof_total 14339
telemt_me_idle_close_by_peer_total 14339
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 200271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536531
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1477
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 1092
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 594
telemt_desync_frames_bucket_total{bucket="gt_10"} 500
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14114
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12685
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1394
telemt_user_connections_total{user="hello"} 688182
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 13406849422 (12.49 GB)
telemt_user_octets_to_client{user="hello"} 242331935085 (225.69 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 64383.1 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901707
telemt_connections_bad_total 9644
telemt_handshake_timeouts_total 19811
telemt_upstream_connect_attempt_total 14410
telemt_upstream_connect_success_total 14330
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14777
telemt_me_reconnect_success_total 11091
telemt_me_reader_eof_total 11821
telemt_me_idle_close_by_peer_total 11821
telemt_me_route_drop_no_conn_total 225083
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744057
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2582
telemt_desync_full_logged_total 872
telemt_desync_suppressed_total 1710
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 978
telemt_desync_frames_bucket_total{bucket="gt_10"} 813
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 11339
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11083
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 744098
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 9192885592 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 267258942460 (248.90 GB)
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 134
```