# Server Metrics 2026-03-11 18:41:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 101652.9 (28h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2579221
telemt_connections_bad_total 48538
telemt_handshake_timeouts_total 56688
telemt_upstream_connect_attempt_total 21422
telemt_upstream_connect_success_total 21410
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10483
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5315
telemt_me_reconnect_attempts_total 34162
telemt_me_reconnect_success_total 16281
telemt_me_reader_eof_total 17611
telemt_me_idle_close_by_peer_total 17611
telemt_me_route_drop_no_conn_total 965432
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2359456
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11979
telemt_desync_full_logged_total 3310
telemt_desync_suppressed_total 8669
telemt_desync_frames_bucket_total{bucket="1_2"} 2946
telemt_desync_frames_bucket_total{bucket="3_10"} 4624
telemt_desync_frames_bucket_total{bucket="gt_10"} 4409
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 17021
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16275
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 2357894
telemt_user_connections_current{user="hello"} 1375
telemt_user_octets_from_client{user="hello"} 35229561612 (32.81 GB)
telemt_user_octets_to_client{user="hello"} 668866687756 (622.93 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 101709.5 (28h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964582
telemt_connections_bad_total 16417
telemt_handshake_timeouts_total 85710
telemt_upstream_connect_attempt_total 31500
telemt_upstream_connect_success_total 28533
telemt_upstream_connect_fail_total 2967
telemt_upstream_connect_attempts_per_request{bucket="1"} 31500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2967
telemt_me_keepalive_timeout_total 2827
telemt_me_reconnect_attempts_total 22598
telemt_me_reconnect_success_total 20488
telemt_me_reader_eof_total 21687
telemt_me_idle_close_by_peer_total 21684
telemt_me_route_drop_no_conn_total 364535
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804730
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3183
telemt_desync_full_logged_total 1028
telemt_desync_suppressed_total 2155
telemt_desync_frames_bucket_total{bucket="1_2"} 1000
telemt_desync_frames_bucket_total{bucket="3_10"} 1138
telemt_desync_frames_bucket_total{bucket="gt_10"} 1045
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20775
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20465
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 807182
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 9739944038 (9.07 GB)
telemt_user_octets_to_client{user="hello"} 232706478452 (216.72 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 101709.5 (28h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1659602
telemt_connections_bad_total 10438
telemt_handshake_timeouts_total 133297
telemt_upstream_connect_attempt_total 26386
telemt_upstream_connect_success_total 26058
telemt_upstream_connect_fail_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 26386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 328
telemt_me_keepalive_timeout_total 1957
telemt_me_reconnect_attempts_total 46890
telemt_me_reconnect_success_total 19859
telemt_me_reader_eof_total 21560
telemt_me_idle_close_by_peer_total 21560
telemt_me_route_drop_no_conn_total 603603
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1452721
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4003
telemt_desync_full_logged_total 1170
telemt_desync_suppressed_total 2833
telemt_desync_frames_bucket_total{bucket="1_2"} 939
telemt_desync_frames_bucket_total{bucket="3_10"} 1519
telemt_desync_frames_bucket_total{bucket="gt_10"} 1545
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20980
telemt_me_refill_failed_total 839
telemt_me_writer_restored_same_endpoint_total 19847
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1121
telemt_user_connections_total{user="hello"} 1452395
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 18031425065 (16.79 GB)
telemt_user_octets_to_client{user="hello"} 442751936633 (412.34 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 101710.0 (28h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1181890
telemt_connections_bad_total 78194
telemt_handshake_timeouts_total 109447
telemt_upstream_connect_attempt_total 27316
telemt_upstream_connect_success_total 27316
telemt_upstream_connect_attempts_per_request{bucket="1"} 27316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1416
telemt_me_reconnect_attempts_total 26856
telemt_me_reconnect_success_total 22246
telemt_me_reader_eof_total 23633
telemt_me_idle_close_by_peer_total 23632
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 394279
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959749
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2023
telemt_desync_full_logged_total 773
telemt_desync_suppressed_total 1250
telemt_desync_frames_bucket_total{bucket="1_2"} 731
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 593
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 22626
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22213
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 959010
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 11402307872 (10.62 GB)
telemt_user_octets_to_client{user="hello"} 291667242792 (271.64 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 6385.8 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106973
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 632
telemt_upstream_connect_attempt_total 1768
telemt_upstream_connect_success_total 1767
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1410
telemt_me_reconnect_success_total 1394
telemt_me_reader_eof_total 1421
telemt_me_idle_close_by_peer_total 1421
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 36592
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98640
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 215
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_restored_same_endpoint_total 1371
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 98618
telemt_user_connections_current{user="hello"} 616
telemt_user_octets_from_client{user="hello"} 6341851624 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 34255301852 (31.90 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 108
```