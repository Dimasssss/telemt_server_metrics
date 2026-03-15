# Server Metrics 2026-03-15 17:08:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 68060.2 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2350414
telemt_connections_bad_total 145337
telemt_handshake_timeouts_total 29415
telemt_upstream_connect_attempt_total 13338
telemt_upstream_connect_success_total 13281
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 14769
telemt_me_reconnect_success_total 9872
telemt_me_reader_eof_total 10554
telemt_me_idle_close_by_peer_total 10554
telemt_me_route_drop_no_conn_total 810143
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1967017
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7717
telemt_desync_full_logged_total 2097
telemt_desync_suppressed_total 5620
telemt_desync_frames_bucket_total{bucket="1_2"} 1878
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 2878
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10191
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9861
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 1966509
telemt_user_connections_current{user="hello"} 2544
telemt_user_octets_from_client{user="hello"} 28880514248 (26.90 GB)
telemt_user_octets_to_client{user="hello"} 746947998988 (695.65 GB)
telemt_user_unique_ips_current{user="hello"} 699
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 68060.8 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 909849
telemt_connections_bad_total 48744
telemt_handshake_timeouts_total 61544
telemt_upstream_connect_attempt_total 17133
telemt_upstream_connect_success_total 17048
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 17133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7797
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14483
telemt_me_reconnect_success_total 13286
telemt_me_reader_eof_total 14059
telemt_me_idle_close_by_peer_total 14059
telemt_me_route_drop_no_conn_total 235112
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701677
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2170
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1441
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 811
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13496
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13274
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 701918
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 10101850191 (9.41 GB)
telemt_user_octets_to_client{user="hello"} 265925929564 (247.66 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 68060.8 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2046348
telemt_connections_bad_total 49329
telemt_handshake_timeouts_total 204574
telemt_upstream_connect_attempt_total 14822
telemt_upstream_connect_success_total 14753
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12581
telemt_me_reconnect_success_total 11312
telemt_me_reader_eof_total 11983
telemt_me_idle_close_by_peer_total 11983
telemt_me_route_drop_no_conn_total 530243
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1252689
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3219
telemt_desync_full_logged_total 1158
telemt_desync_suppressed_total 2061
telemt_desync_frames_bucket_total{bucket="1_2"} 738
telemt_desync_frames_bucket_total{bucket="3_10"} 1246
telemt_desync_frames_bucket_total{bucket="gt_10"} 1235
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11510
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11293
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 198
telemt_user_connections_total{user="hello"} 1248623
telemt_user_connections_current{user="hello"} 1530
telemt_user_octets_from_client{user="hello"} 19263927048 (17.94 GB)
telemt_user_octets_to_client{user="hello"} 446107867116 (415.47 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 68060.7 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 974095
telemt_connections_bad_total 81112
telemt_handshake_timeouts_total 47768
telemt_upstream_connect_attempt_total 169349
telemt_upstream_connect_success_total 168801
telemt_upstream_connect_fail_total 548
telemt_upstream_connect_attempts_per_request{bucket="1"} 169349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 548
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 58746
telemt_me_reconnect_success_total 13323
telemt_me_reader_eof_total 15099
telemt_me_idle_close_by_peer_total 15099
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 226041
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 600983
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1706
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 441
telemt_desync_frames_bucket_total{bucket="3_10"} 662
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14881
telemt_me_refill_failed_total 1421
telemt_me_writer_restored_same_endpoint_total 13287
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1558
telemt_user_connections_total{user="hello"} 752607
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 14182186846 (13.21 GB)
telemt_user_octets_to_client{user="hello"} 270349290985 (251.78 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 68062.2 (18h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 987290
telemt_connections_bad_total 12073
telemt_handshake_timeouts_total 22040
telemt_upstream_connect_attempt_total 15102
telemt_upstream_connect_success_total 15020
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15295
telemt_me_reconnect_success_total 11602
telemt_me_reader_eof_total 12375
telemt_me_idle_close_by_peer_total 12375
telemt_me_route_drop_no_conn_total 246783
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816680
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2766
telemt_desync_full_logged_total 931
telemt_desync_suppressed_total 1835
telemt_desync_frames_bucket_total{bucket="1_2"} 855
telemt_desync_frames_bucket_total{bucket="3_10"} 1034
telemt_desync_frames_bucket_total{bucket="gt_10"} 877
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11857
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11594
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 816714
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 10064068364 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 289462649344 (269.58 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 112
```