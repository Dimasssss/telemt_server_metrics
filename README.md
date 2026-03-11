# Server Metrics 2026-03-11 06:06:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 56355.3 (15h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1106882
telemt_connections_bad_total 13232
telemt_handshake_timeouts_total 38130
telemt_upstream_connect_attempt_total 11958
telemt_upstream_connect_success_total 11949
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 689
telemt_me_reconnect_attempts_total 20767
telemt_me_reconnect_success_total 9086
telemt_me_reader_eof_total 9883
telemt_me_idle_close_by_peer_total 9883
telemt_me_route_drop_no_conn_total 407209
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 993005
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4605
telemt_desync_full_logged_total 1300
telemt_desync_suppressed_total 3305
telemt_desync_frames_bucket_total{bucket="1_2"} 1268
telemt_desync_frames_bucket_total{bucket="3_10"} 1738
telemt_desync_frames_bucket_total{bucket="gt_10"} 1599
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9534
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9080
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 992676
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 13346473752 (12.43 GB)
telemt_user_octets_to_client{user="hello"} 291980619148 (271.93 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 56412.1 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426107
telemt_connections_bad_total 4135
telemt_handshake_timeouts_total 20628
telemt_upstream_connect_attempt_total 20600
telemt_upstream_connect_success_total 17693
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7528
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 2007
telemt_me_reconnect_attempts_total 12739
telemt_me_reconnect_success_total 11916
telemt_me_reader_eof_total 12592
telemt_me_idle_close_by_peer_total 12590
telemt_me_route_drop_no_conn_total 196416
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365274
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1908
telemt_desync_full_logged_total 570
telemt_desync_suppressed_total 1338
telemt_desync_frames_bucket_total{bucket="1_2"} 597
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12054
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11894
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 367544
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 3699380182 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 89933385972 (83.76 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 56411.9 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727858
telemt_connections_bad_total 6229
telemt_handshake_timeouts_total 40139
telemt_upstream_connect_attempt_total 15264
telemt_upstream_connect_success_total 15063
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 15264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6780
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 22236
telemt_me_reconnect_success_total 11163
telemt_me_reader_eof_total 12042
telemt_me_idle_close_by_peer_total 12042
telemt_me_route_drop_no_conn_total 245218
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 650068
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1841
telemt_desync_full_logged_total 532
telemt_desync_suppressed_total 1309
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 11653
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 11152
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 650922
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 7793403529 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 192426114501 (179.21 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 56412.3 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553695
telemt_connections_bad_total 52949
telemt_handshake_timeouts_total 57560
telemt_upstream_connect_attempt_total 16154
telemt_upstream_connect_success_total 16154
telemt_upstream_connect_attempts_per_request{bucket="1"} 16154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 640
telemt_me_reconnect_attempts_total 14373
telemt_me_reconnect_success_total 13328
telemt_me_reader_eof_total 14149
telemt_me_idle_close_by_peer_total 14149
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 164121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428273
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 911
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 337
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 13481
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 13306
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 427850
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 5197834124 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 118148444396 (110.03 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 56412.1 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578551
telemt_connections_bad_total 5959
telemt_handshake_timeouts_total 3906
telemt_upstream_connect_attempt_total 16148
telemt_upstream_connect_success_total 16081
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 16148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7699
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 665
telemt_me_reconnect_attempts_total 16922
telemt_me_reconnect_success_total 13139
telemt_me_reader_eof_total 13876
telemt_me_idle_close_by_peer_total 13876
telemt_me_route_drop_no_conn_total 188952
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 528097
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2543
telemt_desync_full_logged_total 984
telemt_desync_suppressed_total 1559
telemt_desync_frames_bucket_total{bucket="1_2"} 915
telemt_desync_frames_bucket_total{bucket="3_10"} 1087
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 13425
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13139
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 527836
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 9353438023 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 184028060178 (171.39 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 82
```