# Server Metrics 2026-03-13 15:20:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 120132.2 (33h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3730041
telemt_connections_bad_total 37421
telemt_handshake_timeouts_total 75347
telemt_upstream_connect_attempt_total 23418
telemt_upstream_connect_success_total 23283
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2193
telemt_me_reconnect_attempts_total 27397
telemt_me_reconnect_success_total 17309
telemt_me_reader_eof_total 18603
telemt_me_idle_close_by_peer_total 18602
telemt_me_route_drop_no_conn_total 1384804
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3418185
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13898
telemt_desync_full_logged_total 3667
telemt_desync_suppressed_total 10231
telemt_desync_frames_bucket_total{bucket="1_2"} 3495
telemt_desync_frames_bucket_total{bucket="3_10"} 5267
telemt_desync_frames_bucket_total{bucket="gt_10"} 5136
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 17863
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17296
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3417972
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 46725057628 (43.52 GB)
telemt_user_octets_to_client{user="hello"} 1076364182624 (1002.44 GB)
telemt_user_unique_ips_current{user="hello"} 473
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 19795.9 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283164
telemt_connections_bad_total 14653
telemt_handshake_timeouts_total 7400
telemt_upstream_connect_attempt_total 4701
telemt_upstream_connect_success_total 4616
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2203
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 5889
telemt_me_reconnect_success_total 3598
telemt_me_reader_eof_total 3818
telemt_me_idle_close_by_peer_total 3818
telemt_me_route_drop_no_conn_total 102346
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253788
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 967
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 719
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3712
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3591
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 253812
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 2543270952 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 71624101100 (66.71 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 149752.7 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2764285
telemt_connections_bad_total 27531
telemt_handshake_timeouts_total 183230
telemt_upstream_connect_attempt_total 33679
telemt_upstream_connect_success_total 33669
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3267
telemt_me_reconnect_attempts_total 28423
telemt_me_reconnect_success_total 25874
telemt_me_reader_eof_total 27440
telemt_me_idle_close_by_peer_total 27439
telemt_me_route_drop_no_conn_total 933778
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2268627
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8070
telemt_desync_full_logged_total 2669
telemt_desync_suppressed_total 5401
telemt_desync_frames_bucket_total{bucket="1_2"} 1274
telemt_desync_frames_bucket_total{bucket="3_10"} 2942
telemt_desync_frames_bucket_total{bucket="gt_10"} 3854
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 26175
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25833
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 301
telemt_user_connections_total{user="hello"} 2268026
telemt_user_connections_current{user="hello"} 947
telemt_user_octets_from_client{user="hello"} 37518075504 (34.94 GB)
telemt_user_octets_to_client{user="hello"} 797334261857 (742.58 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 149753.3 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1760739
telemt_connections_bad_total 18132
telemt_handshake_timeouts_total 133673
telemt_upstream_connect_attempt_total 47279
telemt_upstream_connect_success_total 44949
telemt_upstream_connect_fail_total 2193
telemt_upstream_connect_attempts_per_request{bucket="1"} 47005
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2192
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11866
telemt_me_reconnect_attempts_total 40605
telemt_me_reconnect_success_total 31633
telemt_me_reader_eof_total 33981
telemt_me_idle_close_by_peer_total 33974
telemt_me_route_drop_no_conn_total 631111
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1469695
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2955
telemt_desync_full_logged_total 956
telemt_desync_suppressed_total 1999
telemt_desync_frames_bucket_total{bucket="1_2"} 792
telemt_desync_frames_bucket_total{bucket="3_10"} 1225
telemt_desync_frames_bucket_total{bucket="gt_10"} 938
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 32154
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31609
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 1474406
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 22974444609 (21.40 GB)
telemt_user_octets_to_client{user="hello"} 565464964262 (526.63 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 19188.6 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307452
telemt_connections_bad_total 3974
telemt_handshake_timeouts_total 2841
telemt_upstream_connect_attempt_total 4135
telemt_upstream_connect_success_total 4007
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 4135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 13578
telemt_me_reconnect_success_total 3004
telemt_me_reader_eof_total 3381
telemt_me_idle_close_by_peer_total 3381
telemt_me_route_drop_no_conn_total 121990
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287940
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 891
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 319
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3349
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3000
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 345
telemt_user_connections_total{user="hello"} 287919
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 3309445520 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 91928042588 (85.61 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 92
```